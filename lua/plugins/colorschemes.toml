return { 
  -- {
  --   "scottmckendry/cyberdream.nvim",
  --   -- dev = true,
  --   lazy = false,
  --   priority = 1000,
  --   config = function()
  --     require("cyberdream").setup({
  --       transparent = true,
  --       italic_comments = true,
  --       hide_fillchars = true,
  --       terminal_colors = false,
  --       cache = true,
  --       borderless_telescope = { border = false, style = "flat" },
  --       theme = {
  --         variant = "auto",
  --         overrides = function(colours)
  --           return {
  --             TelescopePromptPrefix = { fg = colours.blue },
  --             TelescopeMatching = { fg = colours.cyan },
  --             TelescopeResultsTitle = { fg = colours.blue },
  --             TelescopePromptCounter = { fg = colours.cyan },
  --             TelescopePromptTitle = { fg = colours.bg, bg = colours.blue, bold = true },
  --           }
  --         end,
  --       },
  --     })
  --     vim.cmd("colorscheme cyberdream")
  --     vim.api.nvim_set_keymap("n", "<leader>tt", ":CyberdreamToggleMode<CR>", { noremap = true, silent = true })
  --     vim.api.nvim_create_autocmd("User", {
  --       pattern = "CyberdreamToggleMode",
  --       callback = function(ev)
  --         print("Switched to " .. ev.data .. " mode!")
  --       end,
  --     })
  --   end,
  -- }, 

 {
  "oxfist/night-owl.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    require("night-owl").setup({
      -- These are the default settings
      bold = true,
      italics = true,
      underline = false,
      undercurl = false,
      transparent_background = true,
    })
    vim.cmd.colorscheme("night-owl")
  end,
}, 

-- {
--   "folke/tokyonight.nvim",
--   lazy = false,
--   priority = 1000,
--   config = function()
--     require("tokyonight").setup({
--       -- your configuration comes here
--       -- or leave it empty to use the default settings
--       style = "night", -- The theme comes in three styles, `storm`, `moon`, a darker variant `night` and `day`
--       transparent = true, -- Enable this to disable setting the background color
--       terminal_colors = true, -- Configure the colors used when opening a `:terminal` in Neovim
--       styles = {
--         -- Style to be applied to different syntax groups
--         -- Value is any valid attr-list value for `:help nvim_set_hl`
--         comments = { italic = true },
--         keywords = { italic = true },
--         functions = {},
--         variables = {},
--         -- Background styles. Can be "dark", "transparent" or "normal"
--         sidebars = "transparent", -- style for sidebars, see below
--         floats = "transparent", -- style for floating windows
--       },
--       sidebars = { "qf", "help", "nvimtree" }, -- Set a darker background on sidebar-like windows. For example: `["qf", "vista_kind", "terminal", "packer"]`
--       day_brightness = 0.3, -- Adjusts the brightness of the colors of the **Day** style. Number between 0 and 1, from dull to vibrant colors
--       hide_inactive_statusline = false, -- Enabling this option, will hide inactive statuslines and replace them with a thin border instead. Should work with the standard **StatusLine** and **LuaLine**.
--       dim_inactive = false, -- dims inactive windows
--       lualine_bold = false, -- When `true`, section headers in the lualine theme will be bold

--       --- You can override specific color groups to use other groups or a hex color
--       --- function will be called with a ColorScheme table
--       ---@param colors ColorScheme
--       on_colors = function(colors) end,

--       --- You can override specific highlights to use other groups or a hex color
--       --- function will be called with a Highlights and ColorScheme table
--       ---@param highlights Highlights
--       ---@param colors ColorScheme
--       on_highlights = function(highlights, colors) end,
--     })
--     vim.cmd [[colorscheme tokyonight]]
--   end
-- },

-- {
--   "marko-cerovac/material.nvim",
--   lazy = false,
--   priority = 1000,
--   config = function()
--     require('material').setup({

--       contrast = {
--           terminal = false, -- Enable contrast for the built-in terminal
--           sidebars = false, -- Enable contrast for sidebar-like windows ( for example Nvim-Tree )
--           floating_windows = false, -- Enable contrast for floating windows
--           cursor_line = false, -- Enable darker background for the cursor line
--           lsp_virtual_text = false, -- Enable contrasted background for lsp virtual text
--           non_current_windows = false, -- Enable contrasted background for non-current windows
--           filetypes = {}, -- Specify which filetypes get the contrasted (darker) background
--       },

--       styles = { -- Give comments style such as bold, italic, underline etc.
--           comments = { --[[ italic = true ]] },
--           strings = { --[[ bold = true ]] },
--           keywords = { --[[ underline = true ]] },
--           functions = { --[[ bold = true, undercurl = true ]] },
--           variables = {},
--           operators = {},
--           types = {},
--       },

--       plugins = { -- Uncomment the plugins that you use to highlight them
--           -- Available plugins:
--           -- "coc",
--           -- "colorful-winsep",
--           -- "dap",
--           -- "dashboard",
--           -- "eyeliner",
--           -- "fidget",
--           -- "flash",
--           -- "gitsigns",
--           -- "harpoon",
--           -- "hop",
--           -- "illuminate",
--           -- "indent-blankline",
--           -- "lspsaga",
--           -- "mini",
--           -- "neogit",
--           -- "neotest",
--           -- "neo-tree",
--           -- "neorg",
--           -- "noice",
--           -- "nvim-cmp",
--           -- "nvim-navic",
--           -- "nvim-tree",
--           -- "nvim-web-devicons",
--           -- "rainbow-delimiters",
--           -- "sneak",
--           -- "telescope",
--           -- "trouble",
--           -- "which-key",
--           -- "nvim-notify",
--       },

--       disable = {
--           colored_cursor = false, -- Disable the colored cursor
--           borders = false, -- Disable borders between vertically split windows
--           background = true, -- Prevent the theme from setting the background (NeoVim then uses your terminal background)
--           term_colors = false, -- Prevent the theme from setting terminal colors
--           eob_lines = false -- Hide the end-of-buffer lines
--       },

--       high_visibility = {
--           lighter = false, -- Enable higher contrast text for lighter style
--           darker = true -- Enable higher contrast text for darker style
--       },

--       lualine_style = "stealth", -- Lualine style ( can be 'stealth' or 'default' )

--       async_loading = true, -- Load parts of the theme asynchronously for faster startup (turned on by default)

--       custom_colors = nil, -- If you want to override the default colors, set this to a function

--       custom_highlights = {}, -- Overwrite highlights with your own
--   })
--   vim.g.material_style = "darker"
--   vim.cmd [[colorscheme material]]
-- end

-- }
}
