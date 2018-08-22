This utility creates "Directed Graph Markup Language" (DGML) files that represent the actual dependency heirarchy of a given directory of LabVIEW files. It groups them by namespace and, optionally any regex that you want based on the filename.

These files need to be viewed with Visual Studio.

Unfortunately there's currently a bug that prevents vi.lib, user.lib and instr.lib grouping from working quite right in "Prefix Deps Names for Special Paths"; I don't currently have the bandwidth to go back and fix it and it doesn't affect the use case that I wrote this for. (I always just ignore the LabVIEW directory completely, which does work.)