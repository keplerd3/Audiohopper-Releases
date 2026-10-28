# Known issues — v0.1.0-beta.1

## Repeating local recognition can remove sentence-break markers

**Priority:** P1

If local recognition is run again for an already reviewed item, its orange
`//` sentence-break markers may disappear. The current workaround is to remove
and re-import the affected item. The full scope of possible review-data loss is
still under investigation.

## Manually changed sentence breaks can affect audio timing

**Priority:** P1

After manually editing sentence boundaries, playback boundaries for the edited
sentences may not precisely match the intended text. Initial recognition timing
is generally more accurate. This is a Beta limitation in the mapping between
edited text and audio timing.
