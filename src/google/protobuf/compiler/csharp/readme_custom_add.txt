修改过的文件 
1. csharp_field_base.h
2. csharp_map_field.h, csharp_map_field.cc
3. csharp_message.h, csharp_message.cc
4. csharp_message_field.h, csharp_message_field.cc
5. csharp_primitive_field.h, csharp_primitive_field.cc
6. csharp_repeated_enum_field.h, csharp_repeated_enum_field.cc
7. csharp_repeated_message_field.h, csharp_repeated_message_field.cc
8. csharp_repeated_primitive_field.h, csharp_repeated_primitive_field.cc
9. csharp_wrapper_field.h, csharp_wrapper_field.cc

通过查找custom add code 就能找到相应修改
修改完后需要用新的protoc生成include下面的proto文件到C#工程