> IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT!
>
> @Andrey Filchenkov, your attention is required:
>
> 1. review and modify the draft release notes below (especially `Installation` and `Uninstallation` sections),
> - `Readme.html` file will be based on this `readme.md` template file,
> - template expressions like the {{BoxLink}} one will be replaced with an appropriate data during the patch compiling stage,  
> 2. develop the patch,
> 3. assign the 'PSS Patch Available' tag to the appropriate TFS issue(s),
> 4. delete this text,
> 5. add [release TAG](https://github.com/SitecoreSupport/Readme/blob/master/docs/VERSIONING.md) to the commit, 
> 6. review and verify artifacts attached to the release,
>
> IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT! IMPORTANT!

### Permanent link
{{BoxLink}}

### Description
Test 3

### Compatibility
The release was built for and tested with the following Sitecore products in bare condition (no hotfixes, patches or other customizations, unless explicitly specified):
{{CompatibilityInfo}}

### Contents
{{Contents}}

### Installation
For **all Sitecore instances** in the solution:

1. Uninstall previous version of the patch (if installed).
2. **Make a backup** of the files mentioned in `Contents` section and listed in the `installation instruction` (if any).
3. Copy the contents of the `Website` folder from the archive to the `Website` folder of your Sitecore solution, overwrite existing files if any conflicts occur.
4. (Optional) Copy the `{{PatchFileName}}` archive into the `$(data)/patches` folder permanently.

### Uninstallation
1. Remove the files listed in the `Contents` section.
2. Restore the original files from the backup made during installation.

### Important Notes
* The patch should be installed only if recommended by Sitecore Support.
* Any related issues and other feedback should be reported via [support portal](https://support.sitecore.net), check [KB 654910](https://kb.sitecore.net/articles/654910) for details.
* Check [KB 077333](https://kb.sitecore.net/articles/077333) to find more information about Sitecore Patches.
