# Crazy-Shit-YAML-File-DONT-OPEN
The ultimate complex YAML file in the human world, used to test the accuracy of YAML file interpreters.

## Do not use your human brain to read the following document to prevent overloading the brain.
## 不要使用用你的人脑来阅读下面的文件，防止大脑超过负载。

```yaml
# 一般复杂的YAML示例
# General complex YAML examples

settings:
  database:
    host: localhost
    port: 5432
    users:
      - name: admin
        roles: ["read-write", "admin"]
        password: "complex&*^%$#@!Password"
      - name: readonly
        roles: ["read-only"]
        password: "anotherComplex*&^%$Password"
    options:
      - enable: true
        name: "logging"
        level: "verbose"
        details: |
          Multiline text
          with special characters: \/*-+?^$.[]{}()|"!

complex_list:
  - item: "First item with `special` characters: @#!"
  - item: |
      Multiline list item
      Line 2
      Line 3 with symbols: %^&*()
  - item: >
      Folded style text
      where new lines are 
      converted to spaces.

mixed_content: 
  key1: "Text with symbols: ~`!@#$%^&*()-_=+[{]}\\|;:'\",<.>/?"
  key2: >
    This is a folded line
    that continues here.
  key3: |
    Literal block of text
    preserving new lines and spaces
    including #: special characters

deep_nesting:
  level1:
    level2:
      level3:
        - item1: "Data"
        - item2: 
            subitem: "More complex data with special chars: \n\t\\"
        - item3:
            sublist:
              - "Nested list"
              - "With multiple items"
              - "And special characters: {}[]()"

special_characters: "Escaped characters: \n, \t, \\, \", \u263A"

# 高度复杂的 YAML 示例
# Highly complex YAML example
globals:
  &default_user { name: default, access: read-only }

users:
  - <<: *default_user
    name: admin
    access: admin
    preferences:
      theme: dark
      notifications: { email: true, sms: false }
      projects: 
        - project1:
            description: "Highly complex project"
            tasks: 
              - task1: 
                  details: "First task"
                  due: 2024-01-01
              - task2:
                  details: "Second task with special chars: ~!@#$"
                  due: 2024-02-01
        - project2:
            description: ">This project is a folded string with spaces."
            tasks:
              - task1:
                  details: |
                    Multiline detail
                    for a single task
                    preserving formats and spaces
                  due: 2024-03-01
      filters:
        - by_status: [open, closed, "in-review"]
        - by_priority: high

deeply_nested:
  level1a:
    level2a:
      level3a:
        level4a:
          level5a: "Five levels deep"
  level1b:
    <<: *default_user
    additional_info: "User with merged globals"
    level2b: 
      level3b: 
        level4b:
          - array_item1
          - array_item2: { nested_key: nested_value }
          - array_item3: 
              - sub_item1
              - sub_item2: "Sub item with special characters: %^&*"

advanced_usage:
  anchored_value: &anchored_value "This is an anchored value"
  reused_value: *anchored_value
  merged_values:
    <<: *default_user
    name: merged_user
    additional_properties: "Properties from the default user are merged here"

custom_tags: !!map {
  ? !!str "key with special chars: @#$%"
  : !!seq [
    !!int 1,
    !!str "String with special tag",
    !!float 3.14,
    !!null "Explicitly null"
  ]
}

# 人类历史上最复杂的 YAML 文件
# The most complex YAML file in human history
ultimate_complexity:
  basic_types:
    string: "String with special characters: ~`!@#$%^&*()_-+={}[]|\\:;'<>,.?/"
    integer: 12345
    float: 123.456
    boolean: true
    null_value: null
  special_characters: "含有转义序列：\n, \t, \\, \", \u263A 和非打印字符"
  anchors_aliases_and_merges:
    default_settings: &default_settings
      theme: "dark"
      notifications: 
        email: true
        sms: false
    user_profile: &user_profile
      name: user123
      email: "user123@example.com"
      settings: 
        <<: *default_settings
        customizations:
          font_size: "14px"
  deep_nesting:
    level_1:
      level_2:
        level_3:
          level_4:
            level_5:
              level_6:
                level_7:
                  level_8:
                    level_9:
                      level_10:
                        deeply_nested_key: "Reached level 10"
  complex_lists_and_dictionaries:
    - item_1: "Simple item"
    - item_2:
        sub_item: 
          - list_in_a_list:
              - "Nested list item 1"
              - "Nested list item 2"
          - another_sub_item: "With special chars: {}[]()"
    - item_3:
        <<: *user_profile
        contributions:
          - project_1: "Contribution to project 1"
          - project_2: "Contribution to project 2"
  custom_tags_and_folded_text:
    folded_text: >
      This is a very long and complex folded text that spans multiple lines in the YAML file,
      but it is displayed as a single line in the interpreted output. This text includes
      various special characters and sequences, such as: \n, \t, \\, and \".
    custom_tagged_object: !!map {
      custom_key: !!str "This key has a custom tag",
      custom_list: !!seq [
        !!int 1,
        !!float 2.345,
        !!bool true,
        !!null null
      ]
    }
  replicated_structures:
    - &replicated_structure
      name: "Replica 1"
      details: "This structure is replicated with aliases."
    - *replicated_structure
    - *replicated_structure
  mixed_content:
    key_with_special_chars: "@#$%^&*()_+{}|:\"<>?-=[]\\;',./`~"
    mixed_data_types:
      - "String with special characters"
      - 12345
      - 678.90
      - true
      - null
      - { nested_dict: "With a string", and_an_array: [1, 2, 3] }

###@~ 注意: 
####$// 这个 YAML 文件是为了展:"..//#示 YAML }
#####* // 语法和结构的复杂性而!&@设计的，&^!_=19
######% 不推荐\n, \t在实际项目中使用如此!@复杂|\/的,.&结构。

###@~ Note:
####$// This YAML file is to display: "..//# YAML }
#####* // Designed by !&@ for the complexity of syntax and structure,&^!_=19
######% It is not recommended\n, \tUse such !@complex|\/,.& structure in actual projects.


```
