YAMG
====

Yet Another Markdown Generator

This is a simple markdown generator in Lua, with support for ToC (Table of Contents) insertion.

##Usage##

    local markdown = require 'markdown'
    local text = [[
        # Title goes here #
        Hello, world!
    ]]
    html = markdown(text)
