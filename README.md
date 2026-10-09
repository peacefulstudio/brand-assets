# brand-assets

Images that Peaceful Studio links to from forums, announcements and READMEs.

## Layout

```
logos/
  peaceful-studio/   logo.svg, logo.png, logo-on-dark.png
  csharp/            logo.svg, logo.png
announcements/
  canton-dotnet-sdk-0.6.0/   pipeline.png, pipeline.svg, quickstart.png, quickstart.svg
```

- `logo-on-dark.png` is the Peaceful Studio logo with a white, black-outlined wordmark, readable on any background.
- PNG files are high-resolution exports: set the display width in the post (logos 96 to 180 px, diagrams 700 px). Diagrams are 64-colour PNG-8.
- SVG files are the editable masters. Forums and email clients do not render SVG, so link the PNG there.

## Linking

Link to a commit, never to `main`, so the picture cannot change under a published post:

```
https://raw.githubusercontent.com/peacefulstudio/brand-assets/<commit-sha>/<path>
```

Add new announcements under `announcements/<project>-<version>/`. Do not edit or delete a file that a published post links to; add a new file instead.

## Licence

The Peaceful Studio logo is a trademark of Peaceful Studio. The C# logo belongs to Microsoft.
