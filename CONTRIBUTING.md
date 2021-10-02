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
