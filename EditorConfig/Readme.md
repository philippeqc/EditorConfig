

|Applied on...|Format|Clean Up|Code Fix|
|---|---|---|---|
|   |Ctrl+E, D|Ctrl+K, Ctrl+E|Ctrl+ ., Enter|
|Standard| x | x | x |
|Formatting| x | x | x |
|Language |   | x | x |
|Naming |   |   | x |

Standard and Formatting conventions can also be applied using a `dotnet format` global tool.

// format folder
dotnet format -f {folder}

// format specific project / solution
dotnet format -f {project_path|solution_path}

// format specific files
dotnet format -files {comma_separated_list_of_files}


