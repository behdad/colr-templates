# Proposed COLRv2 templatizer

This is in regards to the proposed COLRv2 paint-templates,
as sketched [here](https://github.com/googlefonts/colr-gradients-spec/issues/371).

To run this code you need a special build of fonttools with
the paint-template changes. You can get those from the
[branch](https://github.com/fonttools/fonttools/tree/colr-paint-template) or
[pull-request](https://github.com/fonttools/fonttools/pull/3242).

The code loads a COLRv1 font (hardcoded as "NotoColorEmoji-Regular.ttf"),
and tries to detect paint graphs that can use templatization, and
proceeds to produce "NotoColorEmoji-Regular-templatized.ttf" with such
templates.  It reports COLR-table size savings.
