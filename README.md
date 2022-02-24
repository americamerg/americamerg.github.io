# caption-generator
Generator making captions so you don't have to

# how to add new categories + captions
1. Go to the function.js file
2. Click on the pencil icon (on the right in the light gray bar right above the lines of code) to edit the file
3. To add a new cateogry, follow the format of the previous ones. The easiest way to do this would be to copy/paste one of the existing ones. Make sure you add a comma to the final ] bracket of the previous category (there won't be one) so it's properly formatted. There should be no comma after the final ] bracket for the last category.
```
'category four name': [
    'My first caption option',
    'My second caption option'
 ],
 'category two name': [
    'My first caption option',
    'My second caption option'
 ],
 'category three name': [
    'My first caption option',
    'My second caption option'
 ]
```
NOTE: To add a category with a special character like an apostrophe or exclamation mark, you have to do a backslash before the apostrophe so it doesn't get confused with the single quotation. For example:
```
'It\'s the best y\'all';
```
4. To add a new caption, follow the format of the previous ones. Make sure you open it up with a single quotation mark and close it with a single quotation mark. There should be a comma outside of the quotation marks for every caption that isn't the final one in a set. Just like the categories, the final one in the set doesn't need a comma.
```
'category four name': [
    'My first caption option',
    'My second caption option',
    'My third caption option',
    'My fourth caption option',
    'My fifth caption option',
    'My sixth caption option',
    'My seventh caption option'
 ],
```
NOTE: To add a caption with a special character like an apostrophe or exclamation mark, you have to do a backslash before the apostrophe so it doesn't get confused with the single quotation. For example:
```
'You\'re too kind\!';
```
5. Once you're happy with your changes, scroll to the bottom of the page and hit the green button "Commit changes" - you can optionally add a message about what you changed for future reference. This can be a very short and concise description; whatever might help if you need to revert back to this version in the future.
6. Wait about a minute, and your changes will be live!

# backlog
1. Consider toggle buttons instead of dropdown
2. Custom dropdown select styling
