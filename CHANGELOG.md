# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### <!-- 1 --> Features

- _(luadev)_ Better vim api completion (#2043)
- Add lualine config for darkplus
- Last updates before 1.0.0 (#1953)
- Use Telescope's git_files with fallback (#2089)
- Plugin version bump (#2120)
- Lazyload notify's configuration (#1855)
- Plugin version bump (#2131)

### <!-- 2 --> Bugfix

- _(installer)_ Backup linked files with rsync (#2081)
- _(installer)_ Check if npm-prefix is writable (#2091)
- _(installer)_ More robust yarn validation (#2113)
- _(lsp)_ Set the handlers opts for v0.6 as well (#2109)
- Bump nvim-tree version
- Formatting
- Remove duplicate lint messages
- Remove autopairs cmp completion (#2083)

### <!-- 3 --> Refactor

- _(bootstrap)_ More robust git module (#2127)
- _(info)_ Use new null-ls api for sources (#2125)
- _(install.sh)_ Fix typo in node error message (#2107)
- _(test)_ Cleanup test utilities (#2132)
- Deprecate lvim.lang.FOO (#1913) (#1914)
- Remove unused old language configs (#2094)
- Uplift neovim's minimum version requirement to 0.6.0 (#2093)
- Avoid running ts.setup in headless (#2119)
- More consistent autocmds (#2133)
- Use a static lvim binary template (#1444)

## [1.0.0-rc]

### <!-- 1 --> Features

- _(installer)_ Nicer rsync output (#2067)
- _(terminal)_ Lazygit can now be toggled (#2039)
- Add lualine config for darkplus
- Last updates before 1.0.0 (#1953)
- Support new null-ls (#1955)
- Empty for empty buffers instead of Buffer <#>
- Improved LSP grouping in lualine
- Decrease hide in width limit for lualine
- Add support for fsharp (#2021)
- Add some messages in uninstall.sh (#1945)
- Null-ls code_actions interface (#2008)
- Full compatibility with neovim v0.6 (#2037)
- Multiple enhancements to lvim-reload (#2054)
- Bump plugin versions (#2064)
- Update lsp-installer and lspconfig hashes to enable solidity_ls language server (#2072)

### <!-- 2 --> Bugfix

- _(autopairs)_ Add missing configuration entries (#2030)
- _(bootstrap)_ Remove hard-coded spellfile option (#2061)
- _(cmp)_ Revert broken sequential loading (#2002)
- _(installer)_ Better handling of existing files (#2066)
- _(lsp)_ Avoid installing an overridden server (#1981)
- _(lsp)_ Prevent repeated setup call (#2048)
- _(lsp)_ Correct client_id parsing in lvim-info (#2071)
- _(lsp)_ Allow overriding servers with custom providers (#2070)
- _(lualine)_ Change `fg` of section `a` in onedarker (#1909)
- _(null-ls)_ Allow the same linter and formatter (#1968)
- _(nvimtree)_ Update settings (#2001)
- _(nvimtree)_ Restore default mappings + make them customizable (#2007)
- _(nvimtree)_ Handle paths containing spaces (#2027)
- _(plugins)_ Typo of pin commit of `treesitter` (#2046)
- _(terminal)_ Allow disabling the open binding for toggleterm
- _(windows)_ Autocmd requires forward slashes (#1967)
- _(windows)_ Remove redundant `resolve` call (#1974)
- Bump nvim-tree version
- Formatting
- Remove duplicate lint messages
- Allow LunarVim changelog to work outside the lvim directory (#1952)
- Use an indepdent shadafile from neovim (#1910)
- Packersync issue when you have large number of plugins (#1922)
- No idea why this breaks barbar
- Lsp root can get very annoying when working with multiple languages. User is still able to turn it on.
- Update jdtls script
- Correct order for cmp's setup (#1999)
- Dont close if next char is a close pair and no pairs in same line (#2017)
- More accessible changelog (#2019)
- Better default, ignore `.git` in `live_grep` (#2020)
- No restart required when changing colorscheme (#2026)
- No longer treat lazygit missing as an error (#2051)

### <!-- 3 --> Refactor

- Deprecate lvim.lang.FOO (#1913) (#1914)
- More configurable format-on-save (#1937)
- Load the default keymaps once (#1965)

<!-- generated by git-cliff -->