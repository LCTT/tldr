# protoc

> 解析 Google Protobuf 文件（`proto` ）并生成特定语言的输出结果

- 从一个 `.proto` 文件生成 Python 代码：

`protoc --python_out={{path/to/output_directory}} {{input_file.proto}}`

- 从一个 `.proto` 文件（导入其它 `.proto` 文件）生成 Java 代码：

`protoc --java_out={{path/to/output_directory}} --proto_path={{path/to/import_search_path}} {{input_file.proto}}`

- 生成多种语言代码：

`protoc --csharp_out={{path/to/c#_output_directory}} --js_out={{path/to/js_output_directory}} {{input_file.proto}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])