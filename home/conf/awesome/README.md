
Most required Libs - 
pcall(require, "luarocks.loader")
local gears         = require("gears")
local awful         = require("awful")
local beautiful     = require("beautiful")
local wibox         = require("wibox")
local freedesktop   = require("freedesktop")
local hotkeys_popup = require("awful.hotkeys_popup")
                      require("awful.hotkeys_popup.keys")
local lain          = require("lain")
local menubar       = require("menubar")

Edit rc.lua "Define apps" And "Define Mod Keys" to change default applications.

Required Packages by Default- brave-browser mpv neofetch cmatrix asciinema ffmpeg cmatrix thunar kate git picom xclip lxappearance