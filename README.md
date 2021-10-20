# changelog-images

Used to add FEATURE/CHANGED/FIXED images to changelog tables in releases across other repos.

Example Markdown:

```
|   |   |
|---|---|
| ![CHANGED](https://raw.githubusercontent.com/concord-consortium/changelog-images/main/changed.png)  | The Admin SDK now requires Node.js 12 or higher. Node.js 10 support has been discontinued.  |
| ![FEATURE](https://raw.githubusercontent.com/concord-consortium/changelog-images/main/feature.png)  | The Admin SDK now exposes a series of ES module entry points. Developers are recommended to import Admin SDK APIs from these entry points. The namespaced version of the API will be removed in a future major release. Refer to the migration guide for details on how to update your existing code to use the new ES module entry points.  |
| ![FEATURE](https://raw.githubusercontent.com/concord-consortium/changelog-images/main/feature.png)  | The new module entry points can be used in native ESM runtimes. You can enable the native ESM support on a server running Node.js 12+ by setting the type: "module" parameter in your project's package.json file. See Node.js documentation for more details.  |
```
