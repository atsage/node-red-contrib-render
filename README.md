# node-red-contrib-render
Node for node-red to render a mustache template passed into the node as msg.template.

Allows for more dynamic rendering than the standard 'template' node, as the template can be passed in as part of the flow itself.

You can use substitutions of the form `{{{payload}}}`, `{{{flow.name}}}` or `{{{global.name}}}` 
