## Modeling

All 3D modeling files and associated drawings should be sorted within this parent folder.

### Common File-types:

- `.shapr`: This is the main file. Other files don't need to be updated when changes are made, but it's in good taste to do so. :)
- `.obj`: The most common export for 3D objects. A standard across a variety of platforms/software. (Found within ZIP files labeled "OBJ Export")
- `.dwg`: The standard "drawing" file type. Used for presenting technical design specifications of 3D models.
- `.pdf`: Usually PDF version of the `.dwg` file type. This is used only for presentation.

### Folder/File Structure

The following structures can be adopted, although coherence is prioritized over consistency (ie: Deviation from these schemes is OK as long as it's understandable):

#### General

- `(Model Type)/`
- - `Drawings/*.(dwg/pdf)`
- - `(Model Project Name).shapr`

A basic structure utilized by the `Environment`.

#### Robot Model

- `(Robot Name) r(Revision #)/`
- - `Drawings/*.(dwg/pdf)`
- - `(Robot Name).shapr`
- - `Technical Specification.md`: Price/Physical Features & improvements.
- - `Assembly.md`: A list of external parts and steps required for complete assembly.
