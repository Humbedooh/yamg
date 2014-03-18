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

### Copyright + License ###
Copyright 2013-2014, Daniel Gruno.
Licensed under the Apache License v/2.
