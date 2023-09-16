# CaptionAssist3D

## A dynamic directional closed captioning system for Unity3D

- Shows the player visually where a sound is coming from and how far away it is.
- Direction is shown via an arrow, distance via the alpha of the caption text.
- Captions are added/removed when the player is out of an AudioSource's range

See it in action: https://www.youtube.com/watch?v=K5czfeyCfJQ&t

![Capture](https://github.com/arboretagames/CaptionAssist3D/assets/132666321/5f6a2348-96f6-4b71-a0e5-f722818d4049)

You are free to:

    Share — copy and redistribute the material in any medium or format
    Adapt — remix, transform, and build upon the material
    for any purpose, even commercially.

Under the following terms:

    Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
    No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

USAGE:

- Add DirectionalCaptionsUI prefab as a child of your player GameObject
- Use the DirectionalSound Source prefab for AudioSources, or add a Directional Sound Caption component to an exisiting AudioSource
- Edit the Caption Text String value to whatever you want the caption for that source to be

https://creativecommons.org/licenses/by/3.0/
