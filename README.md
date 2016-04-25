# Introduction
Table form is a jQuery plugin that can be used to generate HTML form in table.

# How To Use

`<div id="table-form"></div>`
`$('#table-form').tableForm({
    class: 'table table-bordered table-hovered',
    header: {
        Name: {
            type: 'text',
            class: 'form-control',
            name: 'attachment-names[]',
            placeholder: 'Name'
        },
        File: {
            type: 'file',
            name: 'attachment-files[]'
        },
    },
    enableNumber: false,
    enableAction: true,
});`
