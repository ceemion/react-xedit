# react-xedit
A simple utility to edit input contents in place

# Features
Light weight custom popover

# Quick Start

`npm install --save react-xedit` or `yarn add react-xedit`

To use
```javascript
  import React from 'react'
  import { EditableText, EditableCheckBox } from 'react-xedit'

  let options = [
    { name: 'guacamole', checked: true},
    { name: 'burretos', checked: false},
    { name: 'sushi', checked: true}

  ]

  class Demo extends React.Component {
    render() {      
      return(
        <div>
          <EditableText editable={true}>This text is editable</EditableText>
          <EditableCheckBox
            editable={true}
            options={options}
          />
        </div>
      )
    }
  }

```

# Contributing
* Fork this repository & clone locally.
* Create an upstream remote and sync your local copy before you branch.
* Branch for each separate piece of work.
* Push to your origin repository.
* Create a new Pull Request.
