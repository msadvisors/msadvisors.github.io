# Client logos

Optional. A client row works with or without a logo.

To add one:

1. Drop the file here, e.g. `assets/clients/kronox.svg` (SVG preferred; PNG with
   a transparent background also works).
2. In `redesign.html`, find the client's `<li>` in the `#clients` section and
   add the `has-logo` class plus the image:

   ```html
   <li class="has-logo">
     <span class="clients__mark"><img src="assets/clients/kronox.svg" alt="Kronox Lab Sciences Limited"></span>
     <b>Kronox Lab Sciences Limited</b>
     <span class="clients__role">Promoters &middot; change of control &middot; 2026</span>
   </li>
   ```

Without `has-logo` the client's name is set as the mark instead. The logo sits
on a light plate so a dark logo stays legible in the dark theme, and rows keep
their alignment whether or not a given client has one.
