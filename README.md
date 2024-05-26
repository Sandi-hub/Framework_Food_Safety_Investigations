# Framework for Food Safety Investigations

Welcome to the Framework for Food Safety Investigations! This framework systematically outlines potential investigative pathways and pinpoints relevant data sources for identifying contaminated food items and their origins during foodborne disease outbreaks. This repository includes

- The framework as an `.html` document in the folder "diagram". Most entities and relations are contain links to explanations and literature and are thus clickable.
- Explanation and citations about the entities and relations in the folder "notes", stored in markdown format. Within those files links point to additional background information stored in the folder "notes/Knowledge Cards".
- Literature references are stored in the file `notes/Zotero_library.bib`. All citations are formatted according to be used with [Pandoc](https://pandoc.org/), using the citation keys stored in the `.bib` file. For the best experience, use Obsidian with the "Pandoc Reference List" plugin, which nicely displays references of the markdown files.

## 1. Prerequisites

Before you begin, ensure you have the following installed:

- [Obsidian](https://obsidian.md/)
- [Pandoc Reference List](https://github.com/mgmeyers/obsidian-pandoc-reference-list) community plugin for Obsidian

## 2. Setup

### 2.1. Clone the Repository

Clone this repository to your local machine.

### 2.2 Configure the Pandoc Reference List Plugin in Obsidian

1. Open Obsidian and go to Settings.
2. Navigate to Pandoc Reference List settings.
3. Set the “Path to bibliography file” to the `zotero_library.bib` file in this repository: `/path_to_your_cloned_repository/notes/zotero_library.bib`.
4. Now you can view the reference list for each file in the Obsidian sidebar.

### 2.3. Ensure Wikilinks are Enabled in Obsidian

Wikilinks are used extensively in this repository for easy navigation and linking between notes. To ensure they work correctly:

1. Open Obsidian and go to Settings.
2. Navigate to Files & Links.
3. Ensure "Use Wikilinks" is enabled.

### 2.4. Use the Minimal Theme in Obsidian

For the best experience, it is recommended to use the Minimal theme in Obsidian because the alternate checkbox styles are used for the advantages of and limitations, and are otherwise only visible as checked checkboxes.

### 2.5. Use the custom css snippet “overview_tag_colors.css”

To display colors in the Overview.md in accordance with the framework diagram:

    1.	Save the snippet `overview_tag_colors.css` in your Obsidian snippets folder.
    2.	Open Obsidian and go to Settings.
    3.	Navigate to Appearance.
    4.	Scroll down to the “CSS snippets” section and ensure that overview_tag_colors.css is enabled.
