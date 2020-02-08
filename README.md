# lucid-css
A reusable set of SCSS classes, mixins and functions. Heavily inspired by inuitcss.

## Example

```scss
// = Vendor
@import "bourbon/core/bourbon";
@import "lucid-css/lucid";

// = Tools
@import "lucid-css/tools/image";

// = Settings
@import "settings/config";
@import "lucid-css/settings/spacing";
@import "settings/globals";
@import "settings/colors";

// = Generic
@import "lucid-css/generic/reset";
@import "lucid-css/generic/box-sizing";

// = Elements
@import "lucid-css/elements/forms";
@import "lucid-css/elements/images";
@import "lucid-css/elements/page";
@import "lucid-css/elements/tables";

// = Objects
@import "lucid-css/objects/box";
@import "lucid-css/objects/container";
@import "lucid-css/objects/form";
@import "lucid-css/objects/layout";
@import "lucid-css/objects/media";
@import "lucid-css/objects/pack";
@import "lucid-css/objects/piped";
@import "lucid-css/objects/ratio";
@import "lucid-css/objects/table";

// = Components
@import "lucid-css/components/checkbox";
@import "lucid-css/components/error";
@import "lucid-css/components/hint";
@import "lucid-css/components/input";
@import "lucid-css/components/label";
@import "lucid-css/components/radio";
@import "lucid-css/components/required";
@import "lucid-css/components/select";

// = Utilities
@import "lucid-css/utilities/widths";

// = Debug
// @import "lucid-css/generic/debug";
```