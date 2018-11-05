# gnome-desktop

Ansible role to configure the gnome-desktop

Sets:
* Wall paper
* GDM Theme
* Restores traditional Alt-Tab behaviour (non grouping)
* Displays Date in menubar

## Optional Config
The following variables default to true. Set them to false to switch off the indicated functionality.
* `gnome_desktop_autohide_panel`: Hides the gnome panel
* `gnome_desktop_classic_alttab`: Do not group applications when performing alt-tab
* `gnome_desktop_disable_native_scroll`: Disable native scroll
* `gnome_desktop_gdm_theme`: Theme GDM to have a black weave background
* `gnome_desktop_menubar_date`: Show the current date in the gnome menubar

