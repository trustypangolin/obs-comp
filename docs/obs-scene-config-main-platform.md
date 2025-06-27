Purpose:

- Platform camera
- Competitor stats
- Sponsor logos

## Scene
<style>
table, th, td {
  border: 1px solid black;
}
</style>
|  <div style="width:500px">Step</div>                       |             OBS ScreenShot                |
|:-----------------------------------------------------------|:-----------------------------------------:|
| Scene :material-arrow-right: :heavy_plus_sign: (Add Scene) | ![](artifacts/scenes/new-scene.png)       |
| Name the Scene <br><b>Main Platform</b>                    | ![](artifacts/scenes/main-platform/mp-scene-name.png)  |

<hr style="border:2px solid black">

## Groups

- Begin by creating all the groups required

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| Sources :material-arrow-right: :heavy_plus_sign:  (Add Source)    | ![](artifacts/scenes/new-sources.png)                            |
| Create Groups                                                     | ![](artifacts/scenes/sources-new-group.png)                      |
| Create the following Groups in order <b><br><ul>  <li>Test Patterns</li><li>Main Platform Video</li><li>LiftingCast-PlatformR</li><li>LiftingCast-PlatformL</li><li>SponsorsBottomLeft</li><li>SponsorsTopLeft</li></ul></b><br>Note: these will appear in *reverse* order | ![](artifacts/scenes/general-group-name.png) |
| Completed Sources *Group* List and Ordering                       |![](artifacts/scenes/main-platform/mp-group-list.png) |

<hr style="border:2px solid black">

## Sources

### SponsorsTopLeft

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
|||

<hr style="border:2px solid black">

### SponsorsBottomLeft

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
|||

<hr style="border:2px solid black">

### LiftingCast-PlatformR

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| `LiftingCast Platform Right` <br> Contains the following Sources set to the bottom-right of the Scene<br><br>**Note:**Before [Transforms](#transforms) and [Filters](#filters) have been applied, the items will be stacked in their default positions |  ![](artifacts/scenes/main-platform/mp-liftingcast-platformr.png) |
| **1920x2160 (Half-Width 4k)**<br>`Fortitude Barbell\Streaming-Release\2160p-4K\Artifacts\`<br>`solid-painted-concrete-wall-textured-backdrop-half.png`<br><br>Background image. Resolution set for positioning and sizing            | ![](artifacts/scenes/sources-new-image.png)![](artifacts/scenes/main-platform/mp-source-bg-exp.png)![](artifacts/scenes/main-platform/mp-source-bg-properties.png)  |
| **LiveFeed V3 Stats**<br>[https://liftingcast.com/meets/**YOUR MEET ID**/liveFeed/version3](https://liftingcast.com/)<br>Set to the Current **Meet ID** showing Competitor and Lifts<br>Set the Web resolution to 4K **(3840x2160)** | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-livefeed-stats.png)  |
| **LiveFeed V1 Lights**<br>[https://liftingcast.com/meets/**YOUR MEET ID**/liveFeed/](https://liftingcast.com/)<br>Set to the Current **Meet ID** showing the Competitor Lights<br>Set the Web resolution to 4K **(3840x2160)**       | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-livefeed-lights.png)  |

<hr style="border:2px solid black">

### LiftingCast-PlatformL

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| `LiftingCast Platform Left` <br> Contains the following Sources set to the bottom-left of the Scene<br><br>**Note:**Before [Transforms](#transforms) and [Filters](#filters) have been applied, the items will be stacked in their default positions |  ![](artifacts/scenes/main-platform/mp-liftingcast-platforml.png) |
| **1920x2160 (Half-Width 4k)**<br>Use the existing source | ![](artifacts/scenes/sources-new-image.png)![](artifacts/scenes/main-platform/mp-source-add-existing-bg.png)  |
| **LiveFeed V3 Stats**<br>Use the existing source  | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-stats.png)  |
| **LiveFeed V1 Lights**<br>Use the existing source | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-lights.png)  |

<hr style="border:2px solid black">

### Main Platform Video

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
|||

<hr style="border:2px solid black">

### Test Patterns

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
|||

<hr style="border:2px solid black">

### Background

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
|||

<hr style="border:2px solid black">

## Transforms

## Filters

## Transitions
