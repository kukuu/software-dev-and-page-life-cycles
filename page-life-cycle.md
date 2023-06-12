# Page Life Cycle - Client Server Hand Shaking

- Page Request
- Page Start
- Page Initialisation
- Page load
- Validation
- Event Trigers/Handling
- Rendering
- Unload

## What they mean

### Page Request
 When page is requested by the USER, the server checks the request and then compiles the page.

### Page Start
In here, two steps are carried out, namely:
- request
- response

The request holds all the information for the page.

### Page Initialisation
In this phase all the controls on the page are set, and each has a particular identifier (ID), namespace (where necessary) and themes are applied to the pages.

### Page Load
In here all control properties are loaded, and information is set using view and control states.

### Validation
Validation happens when the page execution goes successful, and then it returns true else the execution fails, and will return false.

### Event Handling/Trigger
Event Handling happens in response to validation. In this case, the page is loaded again to enable calling of postback event handler.

### Event Rendering
Rendering occurs before all the response information is sent to the USER. It also stores all the information sent to the USER.

### Page Unload
Unload phase helps to:
- Clean all unwanted information
- Cleans the memory once page is sent to the USER.

## Related Articles
- https://github.com/kukuu/software-dev-life-cycle
- https://github.com/kukuu/software-engineering-best-practices
