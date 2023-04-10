+++
author = "Hido"
title = "First Post"
date = "2023-04-10"
description = "How the first page should look like"
tags = [
    "firstpage",
]

+++


What's wrong with me? I'm trying to write a new post, but the `draft` is set to `true`. What's that?

## What is a draft?

A draft is a post that is not published yet. It's a post that you can write and save, but it's not visible to the public. There are two ways to create a draft: either manually by setting the `draft` front matter to `true` or by using the `new` command with the `--draft` flag.

## How do I create a draft?

You can create a draft by using the `new` command with the `--draft` flag. For example:

    $ hugo new --kind post --draft my-first-draft.md

This command will create a new draft post in the `content/posts` directory.

## How do I publish a draft?

You can publish a draft by removing the `draft` front matter. For example:

    ---
    title: "My First Draft"
    date: 2022-09-05T22:27:36+02:00
    draft: false
    ---

## How do I see a list of all my drafts?

You can see a list of all your drafts by using the `list` command with the `--drafts` flag. For example:

    $ hugo list --drafts

## How do I see a list of all my posts?

You can see a list of all your posts by using the `list` command with the `--posts` flag. For example:

    $ hugo list --posts

## How do I see a list of all my pages?

You can see a list of all your pages by using the `list` command with the `--pages` flag. For example:

    $ hugo list --pages

## How do I see a list of all my content?

You can see a list of all your content by using the `list` command without any flags. For example:

    $ hugo list

## How do I see a list of all my content in a specific section?

You can see a list of all your content in a specific section by using the `list` command with the `--section` flag. For example:

    $ hugo list --section posts

## How do I see a list of all my content in a specific section with a specific kind?

You can see a list of all your content in a specific