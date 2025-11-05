# MapStruct 案例

官网链接: [MapStruct](http://mapstruct.org/)

存在以下案例

> ✅: 表示基本理解
> 🚧: 表示未理解 / 未阅读

- ✅ [_mapstruct-lombok_](mapstruct-lombok): 展示 MapStruct 如何和 Lombok 交互
- ✅ [_mapstruct-iterable-non-iterable_](mapstruct-iterable-to-non-iterable): 展示了如何将可迭代对象映射为非可迭代对象，比如将 `List<Integer> -> Integer`
- ✅ [_mapstruct-mapping-from-map_](mapstruct-mapping-from-map): 展示了几种方法，如使用 MapperUtil 和 Qualifiers 的将 Map 中的值提取并映射. Watch [mapstruct/mapstruct#1075](https://github.com/mapstruct/mapstruct/issues/1075) for native support.
- ✅ [_mapstruct-rounding_](mapstruct-rounding): 展示了几种使用 MapperUtil 和 Qualifiers 将数字(BigDecimal) 映射的方法
- ✅ [_mapstruct-updatemethods_](mapstruct-updatemethods-1): 展示了几种更新实体的方法，Target 实体在参数中，使用 `@MappingTarget` 修饰
- ✅ [_mapstruct-field-mapping_](mapstruct-field-mapping): 展示了 MapStruct 可以配置 `@Mapper(uses={...})` 递归映射
- ✅ [_mapstruct-nested-bean-mappings_](mapstruct-nested-bean-mappings): 展示了字段嵌套映射，可以使用 `target="fish.type"` 这样的表达
- ✅ [_mapstruct-mapping-with-cycles_](mapstruct-mapping-with-cycles): 展示了循环映射
- 🚧 [_mapstruct-spi-accessor-naming_](mapstruct-spi-accessor-naming): Example on how to use the Service Provider Interface (SPI) for a custom accessor naming strategy.
- 🚧 [_mapstruct-protobuf3_](mapstruct-protobuf3): Example on how to use protobuf3 with MapStruct
- 🚧 [_mapstruct-jpa-child-parent_](mapstruct-jpa-child-parent): Example on how to use @Context in relation to parent / child relations in JPA
- 🚧 [_mapstruct-suppress-unmapped_](mapstruct-suppress-unmapped): Shows how mapping to target properties can be ignored without warning by default in a mixed scenario. However bean property mappings that have the same name will still be applied.
- 🚧 [_mapstruct-lookup-entity-with-id_](mapstruct-lookup-entity-with-id): Shows how an object with composite key can be read from the database in a mapping method.
- ✅ [_mapstruct-clone_](mapstruct-clone): 展示了对象可以被深度拷贝的案例
- 🚧 [_mapstruct-metadata-annotations_](mapstruct-metadata-with-annotations): Demonstrates how to read annotations and use them as mapping instruction.
- 🚧 [_mapstruct-mappers-repo_](mapstruct-mapper-repo): Demonstrates how one can build a repo of mappers by means of code generation.
