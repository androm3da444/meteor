{{#template name="pkg_markdown"}}

## `markdown`

This package lets you use Markdown in your templates. It's easy: just
put your markdown inside `{{dstache}}#markdown}} ... {{dstache}}/markdown}}`
tags. You can still use all of the usual Meteor template features
inside a Markdown block, such as `{{dstache}}#each}}`, and you still get
reactivity.

Example:

`{{dstache}}#markdown}}I am using __markdown__.{{dstache}}/markdown}}`

outputs

    <p>I am using <strong>markdown</strong>.</p>

{{/template}}
