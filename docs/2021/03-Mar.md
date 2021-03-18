# March 17, 2021

### Fixes & Improvements

- Hosted mock servers are now accessible from any origin and will not limit any HTTP headers or methods. [Learn more about mocking](https://meta.stoplight.io/docs/platform/3.-design/d.setting-up-a-mock-server.md)
- Unpublished branches will no longer appear for "Guest" members.

# March 16, 2021

### Fixes & Improvements

- Fixed a bug where re-ordering properties of a schema in code-view would not be reflected in form view.

# March 15, 2021

### Fixes & Improvements

- Fixed an error that prevented users from logging in or integrating with their VCS provider.

# March 8, 2021

### Fixes & Improvements

- Fixed deleting a path parameter would cause unexpected Studio behavior (such as redirecting to the API overview page)
- Path parameters will no longer disappear when attempting to change its type.

# March 5, 2021

### Multiple VCS Integrations for the Same Git Provider

For organizations that maintain projects hosted on different VCS servers, such as Github Cloud and Github Enterprise. This feature will allow you to install multiple providers of the same type with different configurations.

![Image](https://github.com/falsaffa/stoplight-release-notes/blob/main/assets/images/2021/MultipleConfigSameVCS.png?raw=true)

# March 3, 2021

### Fixes & Improvements

- Fixed users invited as "Guests" would be granted the role "Viewer" and not guest.
- Fixed HTTP Operation referenced parameters not properly showing in Studio form.