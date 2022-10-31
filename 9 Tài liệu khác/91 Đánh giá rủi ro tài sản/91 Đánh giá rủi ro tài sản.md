---

database-plugin: basic

---

%% dbfolder:yaml
name: new database
description: new description
columns:
  __file__:
    key: __file__
    input: markdown
    label: File
    accessor: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isSorted: true
    isSortedDesc: true
    accessorKey: __file__
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: true
      source_data: current_folder
  Loại_tài_sản:
    input: select
    key: Loại_tài_sản
    accessor: Loại_tài_sản
    label: Loại tài sản
    position: 7
    accessorKey: Loại_tài_sản
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Vật lý", backgroundColor: "hsl(167, 95%, 90%)"}
      - { label: "Số", backgroundColor: "hsl(187, 95%, 90%)"}
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
  Xác_suất_bị_tấn_công:
    input: select
    accessor: Xác_suất_bị_tấn_công
    key: Xác_suất_bị_tấn_công
    label: Xác suất bị tấn công
    position: 4
    isSorted: true
    isSortedDesc: true
    accessorKey: Xác_suất_bị_tấn_công
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Thấp", backgroundColor: "hsl(216, 95%, 90%)"}
      - { label: "Trung bình", backgroundColor: "hsl(179, 95%, 90%)"}
      - { label: "Cao", backgroundColor: "hsl(359, 95%, 90%)"}
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
      source_data: current_folder
  Hệ_quả_khi_đã_bị_tấn_công:
    input: text
    accessor: Hệ_quả_khi_đã_bị_tấn_công
    key: Hệ_quả_khi_đã_bị_tấn_công
    label: Hệ quả khi đã bị tấn công
    position: 5
    accessorKey: Hệ_quả_khi_đã_bị_tấn_công
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
      source_data: current_folder
      task_hide_completed: true
  Độ_ảnh_hưởng_của_hệ_quả:
    input: select
    accessor: Độ_ảnh_hưởng_của_hệ_quả
    key: Độ_ảnh_hưởng_của_hệ_quả
    label: Độ ảnh hưởng của hệ quả
    position: 6
    accessorKey: Độ_ảnh_hưởng_của_hệ_quả
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Thấp", backgroundColor: "hsl(145, 95%, 90%)"}
      - { label: "Trung bình", backgroundColor: "hsl(97, 95%, 90%)"}
      - { label: "Cao", backgroundColor: "hsl(92, 95%, 90%)"}
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
      source_data: current_folder
  newColumn6:
    input: text
    accessor: newColumn6
    key: newColumn6
    label: New Column 6
    position: 2
    accessorKey: newColumn6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: false
      source_data: current_folder
      task_hide_completed: true
  Điểm_tấn_công:
    input: text
    accessor: Điểm_tấn_công
    key: Điểm_tấn_công
    label: Điểm tấn công
    position: 3
    accessorKey: Điểm_tấn_công
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      media_width: 100
      media_height: 100
      isInline: true
      source_data: current_folder
      task_hide_completed: true
config:
  enable_show_state: false
  group_folder_column: 
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  show_metadata_created: false
  show_metadata_modified: false
  source_data: current_folder
  source_form_result: root
  show_metadata_tasks: false
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: 
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  source_destination_path: /
  pagination_size: 10
  formula_folder_path: /
filters:
  enabled: false
  conditions:
%%