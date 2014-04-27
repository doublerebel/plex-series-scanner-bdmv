plex-series-scanner-bdmv
========================

Based on the original Plex Series Scanner with Disc Image Support from Plex Zendesk Docs:
https://plexapp.zendesk.com/hc/en-us/article_attachments/200480707/plex_series_scanner_with_disc_image_support.py

Linked from help article "Scanning Disk Image Format Media":
https://plexapp.zendesk.com/hc/en-us/articles/201674343

This scanner takes the BDMV functionality from the Movie Scanner with Disc Image Support and adds it to the Series Scanner.

### Naming Convention

The parent directory to the BDMV must follow the Plex series naming convention.  If the .m2ts files are in BDMV/STREAM/ then the path would look like this:

    /path/to/series-library/Series.Name.S02.E01-E12/BDMV/STREAM

This is so that the episode range can be specified in the folder, as many BD series are multi-disc sets.

    /path/to/series-library/Series Name Season 2/Series.Name.Disc1.S02.E01-E12/BDMV/STREAM

However, this means the scanner will ignore the parent folder of the disc.  In the above example "Series Name Season 2" is ignored.

### How to use

See "How to Install a Custom Scanner" in the Plex Forums:
https://forums.plex.tv/index.php/topic/19396-how-to-install-a-custom-scanner/

For additional platform-specific information see "Scanning Disk Image Format Media" in the Plex Zendesk Docs:
https://plexapp.zendesk.com/hc/en-us/articles/201674343
