# With new apps

- You will need Hugo
- `hugo new app/appname`
    - The appname must not have any spaces, using the package id is an option
- Fill out the required fields on the generated md file
- Put the optional fields if available
- Put the icon of the app, if the source is not that available for static serving you can download it
- Like the Mixplorer example, you must use absolute urls for icon or it will not show up on the index pages
- Add a description for the app and some screenshots, if the original site provides static file accessible 
 screenshots you can just use the direct link.
- **Each app addition must have it's own PR**
- You can post a lot PRs and review other people PRs if you want

# With template changes
- Each feature change on it's own PR

# About CI
- Vercel generates a staging deploy at every commit so you should see what the result looks like before any 
other human intervention.

# About tags

It's more useful to provide meaningful tags, these are the default tag system that might change later. Should be enforced by code review.
- `downloader`: if it downloads the content to be used inside the application
- `file-manager`: if the main usage is to manage files
- `has-dark-theme`: if the app have some mechanism to change theme to a dark variant
- `has-image-editor`: if the app have some image editing capatibility like crop images
- `has-network-file-transfer`: if the app provides a mechanism to discover other nodes on the same local network to transfer files
- `has-plugin-system`: if the app supports some kind of plugin system, probably using external APK files that the app discovers at runtime
- `reader`: if it reads some kind of document
- `text-editor`: if it has some mechanism for editing plain text files or code
