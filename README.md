# NAIT Theory Plover Dictionary
This is an edit of Plover's default dictionary to align with NAIT theory, for use at home instead of paying for a CaseCat subscription.
## Plugin Requirements
plover-retro-format (to emulate CaseCat number formatting for `TOIM` and `FOIM`)\
plover-q-and-a (for Q&A formatting. The `q_and_a.json` settings file is in this repo as well, although you'll have to manually move it)\
plover-retro-text-transform (for cap back)\
plover-stitching (for stitching)\
You may also want Plover2CAT.
## Changes
Plover does not allow for one outline to do both initial and final quote -- you can either leave `KW-T` as is, and have spaces around both sides of the quote to clean up later, or use default Plover `KW-GS` (initial) and `KR-GS` (final). \
(At the time of writing, you will be docked marks on your notes if you use `KW-GS`/`KR-GS` on tests. Be careful, learn both!)\
You will have to `TOIM` more often than the official CC dictionary -- immediate triggers like `A*PL` and `P*PL` work, but not words before the time (and you'll always have to `FOIM`).\
Q&A formatting is slightly broken compared to CaseCat, so it will not infer question marks after questions and periods after answers. (Sorry. I'll try and figure this out.)
## Other info
If you beg Joanne and Keegan enough, they might let you have the full dictionary early, in which case *don't use this*, convert it to RTF in class and then use that in Plover
