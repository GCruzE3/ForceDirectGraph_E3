# PowerBI-visuals-ForceGraph
[![Build Status](https://github.com/microsoft/PowerBI-visuals-ForceGraph/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/microsoft/PowerBI-visuals-ForceGraph/actions/workflows/build.yml)

> The new version of Force Graph based on the new DevTools/API

![ForceGraph chart screenshot](assets/screenshot.png)
# Overview

The ability to visualize the relationship between items, the weightage of the relationship and the flow often brings out the untold insights into limelight, which are otherwise not very evident. Simple numbers and basic charts won’t be enough to discover and tell such data stories. We need new visualization techniques for the complex world of relationship and Force-Directed Graph thrives to the forefront for such scenarios.

This custom visual implements a D3 force layout diagram with curved paths. The thickness of the path represents the weight of the relationship between the nodes.

Since the relationship and interconnection between large set of entities could be very complex, the visual positions the nodes in such a way that there are few crossings as possible, making the exploration experience easy, fun. The visual also produces the layout which is overall pleasing to the eyes for large data sets. Users can also adjust the layout manually by simply dragging the nodes around.

Ideally you would need two dimensions and one measure (for the weightage) to use with this visual. But this also works just with a single column.

See also [Force-Directed Graph at Microsoft Office store](https://store.office.com/en-us/app.aspx?assetid=WA104380764&sourcecorrid=77983508-5303-4ec4-9df1-2859e60e896c&searchapppos=0&ui=en-US&rs=en-US&ad=US&appredirect=false)
