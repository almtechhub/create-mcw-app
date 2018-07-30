# create-mcw-app
create-mcw-app is an node cli tool to create Material Component Web application from a project template.

## Installation
`npm install -g create-mcw-app`

## Usage
`create-mcw-app <arg1> <arg2>`

### Valid First Argument
1. init
2. npm
3. list
4. open
5. comp

### init
Initializes a new mcw application by cloning a git repo. The app directory will be named what is passed to arg2.

`create-mcw-app init <arg2>`

### npm
Lists the npm install name for a given component.

```bash
create-mcw-app npm <comp>
// @material/<comp>
```

### comp
Lists the github repo link a given component.

```bash
create-mcw-app comp <comp>
// https://github.com/material-components/material-components-web/tree/master/packages/mdc-<comp>
```

### comp
opens the browser to the components github repo.

```bash
create-mcw-app open <comp>
```

### list
Lists all the currently finished, non-deprecated Material Web Components.

## Valid Components
- animation
- auto-init
- base
- button
- card
- checkbox
- chips
- dialog
- drawer
- elevation
- fab
- floating-label
- form-field
- icon-button
- image-list
- layout-grid
- line-ripple
- linear-progress
- list
- menu
- notched-outline
- radio
- ripple
- rtl
- select
- selection-control
- shape
- slider
- snackbar
- switch
- tab-indicator
- tab-scroller
- tab
- tab-bar
- theme
- top-app-bar
- typography

## License
create-mwc-app is released under the MIT license.
