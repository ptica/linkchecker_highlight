Highlight links determined to be broken by the Linkchecker module. A user must
have the "View highlighted broken links" permission to see highlighted broken
links. Obviously, it is recommended that only users who have access to the
broken links report be granted this permission.

Color codes:

Default: White on gray
-110 (Connection timeout): White on gray
0 (Server not found): White on red
301 (Moved): White on blue
403 (Forbidden): Red on black
404 (Page not found): White on red

Highlight colors can be customized simply by adding classes to your theme's
CSS files, like so:

.broken-link-0 {
  color: black;
  background: orange;
}
