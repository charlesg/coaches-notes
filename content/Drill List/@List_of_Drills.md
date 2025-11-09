---

database-plugin: basic

---

```yaml:dbfolder
name: List
description: A list of various coaching drills with notes and attibutes.
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 0
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
  Tags:
    input: tags
    accessorKey: Tags
    key: Tags
    id: Tags
    label: Tags
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 314
    options:
      - { label: "BALANCE", value: "BALANCE", color: "hsl(316, 95%, 90%)"}
      - { label: "PRESSURE", value: "PRESSURE", color: "hsl(238, 95%, 90%)"}
      - { label: "EDGING", value: "EDGING", color: "hsl(217,93%,88%)"}
      - { label: "BRUSHES", value: "BRUSHES", color: "hsl(96, 95%, 90%)"}
      - { label: "GATES", value: "GATES", color: "hsl(188, 95%, 90%)"}
      - { label: "CARVING", value: "CARVING", color: "hsl(49,93%,88%)"}
      - { label: "ROTARY", value: "ROTARY", color: "hsl(38,93%,88%)"}
      - { label: "TIMING", value: "TIMING", color: "hsl(185, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
  Skiils_Quest:
    input: select
    accessorKey: Skiils_Quest
    key: Skiils_Quest
    id: Skiils_Quest
    label: Skiils Quest
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Phase 2", value: "Phase 2", color: "hsl(133, 95%, 90%)"}
      - { label: "Phase 4", value: "Phase 4", color: "hsl(318, 95%, 90%)"}
      - { label: "Phase 3", value: "Phase 3", color: "hsl(21, 95%, 90%)"}
      - { label: "Phase 5", value: "Phase 5", color: "hsl(206,93%,88%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Rating:
    input: text
    accessorKey: Rating
    key: Rating
    id: Rating
    label: Rating
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Notes:
    input: text
    accessorKey: Notes
    key: Notes
    id: Notes
    label: Notes
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 379
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 200
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```