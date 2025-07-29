---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmclto
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# LTO



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOModule * <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a loaded object module <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOCodeGenerator * <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a code generator <a href="#ga6e1ba6da4277057a20e147d9412a03d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueThinLTOCodeGenerator * <a href="#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a thin code generator <a href="#gaad92d29c62685dde82e298596453c415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#gacc8bcb5e44e35ed3a8b8e9f077218c21">lto_diagnostic_handler_t</a>)(lto_codegen_diagnostic_severity_t severity, const char *diag, void *ctxt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic handler type. <a href="#gacc8bcb5e44e35ed3a8b8e9f077218c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOInput * <a href="#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opaque reference to an LTO input file. <a href="#gaa6aff1636eea0cf605498fa8cdd100e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_symbol_attributes { <a href="#ga913b51e895306793f1c843f1385d6d77">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_debug_model { <a href="#ga45b08530a7582678cb4c03bc70a33bae">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_codegen_model { <a href="#gad17a28f0ff971d0c201f4716b25948a4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_codegen_diagnostic_severity_t { <a href="#ga7d1dffbb71e58b376fc879b8098957b3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic severity. <a href="#ga7d1dffbb71e58b376fc879b8098957b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#a4789aaabaa5bf3b7a549171b47cc4d4a">LLVM_C_EXTERN_C_BEGIN</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabea4fdb81db6b16bd57b5da06cb5b5ba">lto_get_version</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a printable string. <a href="#gabea4fdb81db6b16bd57b5da06cb5b5ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last error string or NULL if last operation was successful. <a href="#gae09912101ce40de1049e5bf6355f6137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae07005b7262f934bccb0d13e29ea12a0">lto_module_is_object_file</a> (const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a file is a loadable object file. <a href="#gae07005b7262f934bccb0d13e29ea12a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaae8cb3eaf287d255af45ae7a745dcf5b">lto_module_is_object_file_for_target</a> (const char *path, const char *target_triple_prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a file is a loadable object compiled for requested target. <a href="#gaae8cb3eaf287d255af45ae7a745dcf5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8e393ebb821c5013502483d55c9f990b">lto_module_has_objc_category</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Buffer</span> contains a bitcode file with ObjC code (category or class) in it. <a href="#ga8e393ebb821c5013502483d55c9f990b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaca136d5490410db13e79001020f711df">lto_module_is_object_file_in_memory</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a buffer is a loadable object file. <a href="#gaca136d5490410db13e79001020f711df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa57ab02868d4736b7d5ea5a3c0faacaa">lto_module_is_object_file_in_memory_for_target</a> (const void *mem, size_t length, const char *target_triple_prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a buffer is a loadable object compiled for requested target. <a href="#gaa57ab02868d4736b7d5ea5a3c0faacaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2bce26a37f3a58f5966c327e984e13c2">lto_module_create</a> (const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="#ga2bce26a37f3a58f5966c327e984e13c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga64f951ad0a065f54861970bdf1f8c3fc">lto_module_create_from_memory</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from memory. <a href="#ga64f951ad0a065f54861970bdf1f8c3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9e33f0d18f0736afce91d3ed98132384">lto_module_create_from_memory_with_path</a> (const void *mem, size_t length, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from memory with an extra path argument. <a href="#ga9e33f0d18f0736afce91d3ed98132384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1da5dff4e86f96d4521f8a4aebe079e7">lto_module_create_in_local_context</a> (const void *mem, size_t length, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file in its own context. <a href="#ga1da5dff4e86f96d4521f8a4aebe079e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga05d6a2cd667124de281532624ea6ba8c">lto_module_create_in_codegen_context</a> (const void *mem, size_t length, const char *path, lto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file in the codegen context. <a href="#ga05d6a2cd667124de281532624ea6ba8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga584067ea7910e54e01147d01a7a9cba3">lto_module_create_from_fd</a> (int fd, const char *path, size_t file_size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="#ga584067ea7910e54e01147d01a7a9cba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf414c81bc3bb9b7e890bd4f19ee16a93">lto_module_create_from_fd_at_offset</a> (int fd, const char *path, size_t file_size, size_t map_size, off_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="#gaf414c81bc3bb9b7e890bd4f19ee16a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafea8ec5886536824e8b654a113601917">lto_module_dispose</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all memory internally allocated by the module. <a href="#gafea8ec5886536824e8b654a113601917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga332b4c1bacc474567f2a474ddef3ae62">lto_module_get_target_triple</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns triple string which the object module was compiled under. <a href="#ga332b4c1bacc474567f2a474ddef3ae62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga35e37587fda0ee1e4e90db17956c22f5">lto_module_set_target_triple</a> (lto_module_t mod, const char *triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets triple string with which the object will be codegened. <a href="#ga35e37587fda0ee1e4e90db17956c22f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5a1e077d0ac49bae8a1329a772906998">lto_module_get_num_symbols</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of symbols in the object module. <a href="#ga5a1e077d0ac49bae8a1329a772906998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9adf61162416e60f69bd5165651fa378">lto_module_get_symbol_name</a> (lto_module_t mod, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the ith symbol in the object module. <a href="#ga9adf61162416e60f69bd5165651fa378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga913b51e895306793f1c843f1385d6d77">lto_symbol_attributes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga91598116ef3f8f7772211ed6a85a91b4">lto_module_get_symbol_attribute</a> (lto_module_t mod, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the attributes of the ith symbol in the object module. <a href="#ga91598116ef3f8f7772211ed6a85a91b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5bab2de970d06f8fa7b4c56f8e384161">lto_module_get_linkeropts</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module's linker options. <a href="#ga5bab2de970d06f8fa7b4c56f8e384161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga16718eb3a64b14d3fc6ebdaf119e5875">lto_module_get_macho_cputype</a> (lto_module_t mod, unsigned int *out_cputype, unsigned int *out_cpusubtype)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If targeting mach-o on darwin, this function gets the CPU type and subtype that will end up being encoded in the mach-o header. <a href="#ga16718eb3a64b14d3fc6ebdaf119e5875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5b59ee17299706db881f30ad4ea8e1ee">lto_module_has_ctor_dtor</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function can be used by the linker to check if a given module has any constructor or destructor functions. <a href="#ga5b59ee17299706db881f30ad4ea8e1ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9f570562a736b80813cba9ae10ace299">lto_codegen_set_diagnostic_handler</a> (lto_code_gen_t, lto_diagnostic_handler_t, void *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a diagnostic handler and the related context (void *). <a href="#ga9f570562a736b80813cba9ae10ace299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga31b1a72b22fc9dcca1ecd28c92e3f89d">lto_codegen_create</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiates a code generator. <a href="#ga31b1a72b22fc9dcca1ecd28c92e3f89d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0751ca93aa0745e38238d1907ef749a1">lto_codegen_create_in_local_context</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiate a code generator in its own context. <a href="#ga0751ca93aa0745e38238d1907ef749a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga226045782babbda624255217e4934dae">lto_codegen_dispose</a> (lto_code_gen_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all code generator and all memory it internally allocated. <a href="#ga226045782babbda624255217e4934dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module</a> (lto_code_gen_t cg, lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an object module to the set of modules for which code will be generated. <a href="#gaca40f093d4adbb3dcc24fe7f0056684d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga92adb73abd04aa8c1a3223edc161b4bf">lto_codegen_set_module</a> (lto_code_gen_t cg, lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the object module for code generation. <a href="#ga92adb73abd04aa8c1a3223edc161b4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad42e2035d7309b212f66dd61c17ffed0">lto_codegen_set_debug_model</a> (lto_code_gen_t cg, lto_debug_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets if debug info should be generated. <a href="#gad42e2035d7309b212f66dd61c17ffed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga77f96a4bf050ec91cca0830107ed815b">lto_codegen_set_pic_model</a> (lto_code_gen_t cg, lto_codegen_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets which PIC code model to generated. <a href="#ga77f96a4bf050ec91cca0830107ed815b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae396c8c812ab4d06c76520234be6ce94">lto_codegen_set_cpu</a> (lto_code_gen_t cg, const char *cpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cpu to generate code for. <a href="#gae396c8c812ab4d06c76520234be6ce94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafee8bbe13e5a24fe6f05bf9e34f5365a">lto_codegen_set_assembler_path</a> (lto_code_gen_t cg, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the location of the assembler tool to run. <a href="#gafee8bbe13e5a24fe6f05bf9e34f5365a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga26548a5c0df7b8c3b642637442449b8f">lto_codegen_set_assembler_args</a> (lto_code_gen_t cg, const char **args, int nargs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets extra arguments that libLTO should pass to the assembler. <a href="#ga26548a5c0df7b8c3b642637442449b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac2b8b7c3f5322c232e269c93f4377d70">lto_codegen_add_must_preserve_symbol</a> (lto_code_gen_t cg, const char *symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds to a list of all global symbols that must exist in the final generated code. <a href="#gac2b8b7c3f5322c232e269c93f4377d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga430254fbb8e2da52467fca97173879d8">lto_codegen_write_merged_modules</a> (lto_code_gen_t cg, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a new object file at the specified path that contains the merged contents of all modules added so far. <a href="#ga430254fbb8e2da52467fca97173879d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2046c9820e71ce99f76234359be8df73">lto_codegen_compile</a> (lto_code_gen_t cg, size_t *length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for all added modules into one native object file. <a href="#ga2046c9820e71ce99f76234359be8df73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadfde0ad97850e1479009556404f5bc61">lto_codegen_compile_to_file</a> (lto_code_gen_t cg, const char **name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for all added modules into one native object file. <a href="#gadfde0ad97850e1479009556404f5bc61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaadfca2f414f452b73109c99438c71351">lto_codegen_optimize</a> (lto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs optimization for the merged module. <a href="#gaadfca2f414f452b73109c99438c71351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad07286ee88f734bf57437c9c0f7d4c6a">lto_codegen_compile_optimized</a> (lto_code_gen_t cg, size_t *length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for the optimized merged module into one native object file. <a href="#gad07286ee88f734bf57437c9c0f7d4c6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9022709cbee7447810418cdbbe66d081">lto_api_version</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the runtime API version. <a href="#ga9022709cbee7447810418cdbbe66d081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1e1f6473e0c498f3562c655355e45374">lto_set_debug_options</a> (const char *const *options, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses options immediately, making them available as early as possible. <a href="#ga1e1f6473e0c498f3562c655355e45374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga05ff9b7bf60f4b42ce3f54dd10f12d11">lto_codegen_debug_options</a> (lto_code_gen_t cg, const char *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets options to help debug codegen bugs. <a href="#ga05ff9b7bf60f4b42ce3f54dd10f12d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafb79ab57d848388bea55173ebd9e16ef">lto_codegen_debug_options_array</a> (lto_code_gen_t cg, const char *const *, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as the previous function, but takes every option separately through an array. <a href="#gafb79ab57d848388bea55173ebd9e16ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac16cae88f84b9eb72f1fbbe31a0f90da">lto_initialize_disassembler</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes LLVM disassemblers. <a href="#gac16cae88f84b9eb72f1fbbe31a0f90da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7d0a764a39bdf298b43a75590c4a4073">lto_codegen_set_should_internalize</a> (lto_code_gen_t cg, lto_bool_t ShouldInternalize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets if we should run internalize pass during optimization and code generation. <a href="#ga7d0a764a39bdf298b43a75590c4a4073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1f857dd87f6159db003e7c12c40466ce">lto_codegen_set_should_embed_uselists</a> (lto_code_gen_t cg, lto_bool_t ShouldEmbedUselists)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to embed uselists in bitcode. <a href="#ga1f857dd87f6159db003e7c12c40466ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad18583a45953ea42efd18ab773cda9a0">lto_input_create</a> (const void *buffer, size_t buffer_size, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an LTO input file from a buffer. <a href="#gad18583a45953ea42efd18ab773cda9a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga048da4fd05807227a91a907f8563aa5f">lto_input_dispose</a> (lto_input_t input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all memory internally allocated by the LTO input file. <a href="#ga048da4fd05807227a91a907f8563aa5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga23a95dfd07fbb9f9180b1866be4faba5">lto_input_get_num_dependent_libraries</a> (lto_input_t input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of dependent library specifiers for the given LTO input file. <a href="#ga23a95dfd07fbb9f9180b1866be4faba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf4e64e6d599e7d40b3c05a169def0bdb">lto_input_get_dependent_library</a> (lto_input_t input, size_t index, size_t *size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ith dependent library specifier for the given LTO input file. <a href="#gaf4e64e6d599e7d40b3c05a169def0bdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2221e1ea6d3053c540ccd3eb078ab749">lto_runtime_lib_symbols_list</a> (size_t *size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of libcall symbols that can be generated by LTO that might not be visible from the symbol table of bitcode files. <a href="#ga2221e1ea6d3053c540ccd3eb078ab749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7cd7eb9fdade49e998bef7b80ea6c0e4">LTO_API_VERSION</a>&nbsp;&nbsp;&nbsp;29</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### lto\_code\_gen\_t {#ga6e1ba6da4277057a20e147d9412a03d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueLTOCodeGenerator* lto_code_gen_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>opaque reference to a code generator</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_diagnostic\_handler\_t {#gacc8bcb5e44e35ed3a8b8e9f077218c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* lto_diagnostic_handler_t) (lto_codegen_diagnostic_severity_t severity, const char *diag, void *ctxt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Diagnostic handler type.</p>


<p><span class="doxyComputerOutput">severity</span> defines the severity. <span class="doxyComputerOutput">diag</span> is the actual diagnostic. The diagnostic is not prefixed by any of severity keyword, e.g., 'error: '. <span class="doxyComputerOutput">ctxt</span> is used to pass the context set with the diagnostic handler.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=7</p></dd>
</dl>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_input\_t {#gaa6aff1636eea0cf605498fa8cdd100e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueLTOInput* lto_input_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opaque reference to an LTO input file.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_t {#ga3ce415fd9e8109d4835461c6de1b9d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueLTOModule* lto_module_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>opaque reference to a loaded object module</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_code\_gen\_t {#gaad92d29c62685dde82e298596453c415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueThinLTOCodeGenerator* thinlto_code_gen_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>opaque reference to a thin code generator</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### lto\_codegen\_diagnostic\_severity\_t {#ga7d1dffbb71e58b376fc879b8098957b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum lto_codegen_diagnostic_severity_t </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Diagnostic severity.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DS_ERROR<a id="gga7d1dffbb71e58b376fc879b8098957b3a56df7007d9125bb715a76233ba550933"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DS_WARNING<a id="gga7d1dffbb71e58b376fc879b8098957b3a30389796c848e8df04427fb26ca4d477"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DS_REMARK<a id="gga7d1dffbb71e58b376fc879b8098957b3a2f2659d7b052eff3b70bc3c6d70e67c5"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DS_NOTE<a id="gga7d1dffbb71e58b376fc879b8098957b3a3f49e62e22757ac378175adf24290baa"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=7</p></dd>
</dl>


<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_model {#gad17a28f0ff971d0c201f4716b25948a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum lto_codegen_model </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_CODEGEN_PIC_MODEL_STATIC<a id="ggad17a28f0ff971d0c201f4716b25948a4aea4e17691fe07ad7347aeffcaa53d89f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_CODEGEN_PIC_MODEL_DYNAMIC<a id="ggad17a28f0ff971d0c201f4716b25948a4a44307b2e3794d87c9089bd867165b1bf"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_CODEGEN_PIC_MODEL_DYNAMIC_NO_PIC<a id="ggad17a28f0ff971d0c201f4716b25948a4a0ed08c6a18bf85a247950470e7cf8a9b"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_CODEGEN_PIC_MODEL_DEFAULT<a id="ggad17a28f0ff971d0c201f4716b25948a4ace82248918011b64c7b538e5ccf01390"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_debug\_model {#ga45b08530a7582678cb4c03bc70a33bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum lto_debug_model </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DEBUG_MODEL_NONE<a id="gga45b08530a7582678cb4c03bc70a33baea9c4180379ab2964e5545899510832af6"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_DEBUG_MODEL_DWARF<a id="gga45b08530a7582678cb4c03bc70a33baea4bd5cb0d20be9e3459e946632969ae3e"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_symbol\_attributes {#ga913b51e895306793f1c843f1385d6d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum lto_symbol_attributes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_ALIGNMENT_MASK<a id="gga913b51e895306793f1c843f1385d6d77a3f0fcbf83b631518afdd8edc80717b93"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000001F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_PERMISSIONS_MASK<a id="gga913b51e895306793f1c843f1385d6d77acd3f554150ceb62bae3350b1b9fa310b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x000000E0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_PERMISSIONS_CODE<a id="gga913b51e895306793f1c843f1385d6d77a11dfd51aa9c97237d8db73de3d84034f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x000000A0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_PERMISSIONS_DATA<a id="gga913b51e895306793f1c843f1385d6d77a5a606bbd4404adbdcb751f120fd015a7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x000000C0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_PERMISSIONS_RODATA<a id="gga913b51e895306793f1c843f1385d6d77a735cac45c02f12464d7c19c2d87ff23e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_MASK<a id="gga913b51e895306793f1c843f1385d6d77aefda09a3d1d662dc025f62c50e33d05f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000700)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_REGULAR<a id="gga913b51e895306793f1c843f1385d6d77a21e2c79cca41650135abe1d08b3eb9b7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_TENTATIVE<a id="gga913b51e895306793f1c843f1385d6d77a50b732265a6adb6f39b72b03563b7a7e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_WEAK<a id="gga913b51e895306793f1c843f1385d6d77abe0ee6e732b5d7ce91154761564fae34"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000300)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_UNDEFINED<a id="gga913b51e895306793f1c843f1385d6d77aae9ae2089893696a5ecc717febce6d97"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_DEFINITION_WEAKUNDEF<a id="gga913b51e895306793f1c843f1385d6d77aa432f91fe8ccd278f15424c2ac98c4d1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000500)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_MASK<a id="gga913b51e895306793f1c843f1385d6d77a83d96085648ff6e51eaf5b24f96b552b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00003800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_INTERNAL<a id="gga913b51e895306793f1c843f1385d6d77a3b61e709f1be4fd125e9873582719afa"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_HIDDEN<a id="gga913b51e895306793f1c843f1385d6d77a4343e4b6a05c7b20cf95a18df1aaca4f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00001000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_PROTECTED<a id="gga913b51e895306793f1c843f1385d6d77a5a9953a5d7974ac03e837c14e5f6f621"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00002000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_DEFAULT<a id="gga913b51e895306793f1c843f1385d6d77a2706fd85b61e391cc355dece4372a346"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00001800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_SCOPE_DEFAULT_CAN_BE_HIDDEN<a id="gga913b51e895306793f1c843f1385d6d77a0a2feb4eb11540dce84040448c432c17"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00002800)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_COMDAT<a id="gga913b51e895306793f1c843f1385d6d77a9ec312c503630c75c701e99c4fabc98a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00004000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTO_SYMBOL_ALIAS<a id="gga913b51e895306793f1c843f1385d6d77a3cca7142df10bdd5c31cb2682b0302ec"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00008000)</td>
</tr>

</table>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### lto\_api\_version() {#ga9022709cbee7447810418cdbbe66d081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int lto_api_version (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the runtime API version.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=12</p></dd>
</dl>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_add\_module() {#gaca40f093d4adbb3dcc24fe7f0056684d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_add_module (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an object module to the set of modules for which code will be generated.</p>


<p>Returns true on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<p><span class="doxyComputerOutput">cg</span> and <span class="doxyComputerOutput">mod</span> must both be in the same context. See <em><a href="#ga0751ca93aa0745e38238d1907ef749a1">lto_codegen_create_in_local_context()</a></em> and <em><a href="#ga05d6a2cd667124de281532624ea6ba8c">lto_module_create_in_codegen_context()</a></em>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_add\_must\_preserve\_symbol() {#gac2b8b7c3f5322c232e269c93f4377d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_add_must_preserve_symbol (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds to a list of all global symbols that must exist in the final generated code.</p>


<p>If a function is not listed there, it might be inlined into every usage and optimized away.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_compile() {#ga2046c9820e71ce99f76234359be8df73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * lto_codegen_compile (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, size_t * length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates code for all added modules into one native object file.</p>


<p>This calls lto_codegen_optimize then lto_codegen_compile_optimized.</p>


<p>On success returns a pointer to a generated mach-o/ELF buffer and length set to the buffer size. The buffer is owned by the <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> and will be freed when <a href="#ga226045782babbda624255217e4934dae">lto_codegen_dispose()</a> is called, or <a href="#ga2046c9820e71ce99f76234359be8df73">lto_codegen_compile()</a> is called again. On failure, returns NULL (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_compile\_optimized() {#gad07286ee88f734bf57437c9c0f7d4c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * lto_codegen_compile_optimized (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, size_t * length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates code for the optimized merged module into one native object file.</p>


<p>It will not run any IR optimizations on the merged module.</p>


<p>On success returns a pointer to a generated mach-o/ELF buffer and length set to the buffer size. The buffer is owned by the <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> and will be freed when <a href="#ga226045782babbda624255217e4934dae">lto_codegen_dispose()</a> is called, or <a href="#gad07286ee88f734bf57437c9c0f7d4c6a">lto_codegen_compile_optimized()</a> is called again. On failure, returns NULL (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=12</p></dd>
</dl>


<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_compile\_to\_file() {#gadfde0ad97850e1479009556404f5bc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_compile_to_file (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates code for all added modules into one native object file.</p>


<p>This calls lto_codegen_optimize then lto_codegen_compile_optimized (instead of returning a generated mach-o/ELF buffer, it writes to a file).</p>


<p>The name of the file is written to name. Returns true on error.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=5</p></dd>
</dl>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### lto\_codegen\_create() {#ga31b1a72b22fc9dcca1ecd28c92e3f89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_code_gen_t lto_codegen_create (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instantiates a code generator.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<p>All modules added using <em><a href="#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module()</a></em> must have been created in the same context as the codegen.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_create\_in\_local\_context() {#ga0751ca93aa0745e38238d1907ef749a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_code_gen_t lto_codegen_create_in_local_context (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instantiate a code generator in its own context.</p>


<p>Instantiates a code generator in its own context. Modules added via <em><a href="#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module()</a></em> must have all been created in the same context, using <em><a href="#ga05d6a2cd667124de281532624ea6ba8c">lto_module_create_in_codegen_context()</a></em>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=11</p></dd>
</dl>


<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_debug\_options() {#ga05ff9b7bf60f4b42ce3f54dd10f12d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_debug_options (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets options to help debug codegen bugs.</p>


<p>Since parsing shud only happen once, only one of lto_codegen_debug_options or lto_set_debug_options should be called.</p>


<p>This function takes one or more options separated by spaces. Warning: passing file paths through this function may confuse the argument parser if the paths contain spaces.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_debug\_options\_array() {#gafb79ab57d848388bea55173ebd9e16ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_debug_options_array (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, int number)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as the previous function, but takes every option separately through an array.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=26</p></dd>
</dl>


<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_dispose() {#ga226045782babbda624255217e4934dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_dispose (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Frees all code generator and all memory it internally allocated.</p>


<p>Upon return the <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> is no longer valid.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_optimize() {#gaadfca2f414f452b73109c99438c71351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_optimize (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs optimization for the merged module.</p>


<p>Returns true on error.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=12</p></dd>
</dl>


<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_assembler\_args() {#ga26548a5c0df7b8c3b642637442449b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_assembler_args (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** args, int nargs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets extra arguments that libLTO should pass to the assembler.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=4</p></dd>
</dl>


<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>.</p>

</div>
</div>

### lto\_codegen\_set\_assembler\_path() {#gafee8bbe13e5a24fe6f05bf9e34f5365a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_assembler_path (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the location of the assembler tool to run.</p>


<p>If not set, libLTO will use gcc to invoke the assembler.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_cpu() {#gae396c8c812ab4d06c76520234be6ce94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_cpu (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * cpu)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the cpu to generate code for.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=4</p></dd>
</dl>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_debug\_model() {#gad42e2035d7309b212f66dd61c17ffed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_set_debug_model (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="#ga45b08530a7582678cb4c03bc70a33bae">lto_debug_model</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets if debug info should be generated.</p>


<p>Returns true on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_diagnostic\_handler() {#ga9f570562a736b80813cba9ae10ace299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_diagnostic_handler (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a>, <a href="#gacc8bcb5e44e35ed3a8b8e9f077218c21">lto_diagnostic_handler_t</a>, void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a diagnostic handler and the related context (void *).</p>


<p>This is more general than lto_get_error_message, as the diagnostic handler can be called at anytime within lto.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=7</p></dd>
</dl>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_module() {#ga92adb73abd04aa8c1a3223edc161b4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_module (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the object module for code generation.</p>


<p>This will transfer the ownership of the module to the code generator.</p>


<p><span class="doxyComputerOutput">cg</span> and <span class="doxyComputerOutput">mod</span> must both be in the same context.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=13</p></dd>
</dl>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_pic\_model() {#ga77f96a4bf050ec91cca0830107ed815b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_set_pic_model (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="#gad17a28f0ff971d0c201f4716b25948a4">lto_codegen_model</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets which PIC code model to generated.</p>


<p>Returns true on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_should\_embed\_uselists() {#ga1f857dd87f6159db003e7c12c40466ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_should_embed_uselists (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a> ShouldEmbedUselists)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set whether to embed uselists in bitcode.</p>


<p>Sets whether <em><a href="#ga430254fbb8e2da52467fca97173879d8">lto_codegen_write_merged_modules()</a></em> should embed uselists in output bitcode. This should be turned on for all -save-temps output.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=15</p></dd>
</dl>


<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_set\_should\_internalize() {#ga7d0a764a39bdf298b43a75590c4a4073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_codegen_set_should_internalize (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a> ShouldInternalize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets if we should run internalize pass during optimization and code generation.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=14</p></dd>
</dl>


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_codegen\_write\_merged\_modules() {#ga430254fbb8e2da52467fca97173879d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_codegen_write_merged_modules (<a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes a new object file at the specified path that contains the merged contents of all modules added so far.</p>


<p>Returns true on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=5</p></dd>
</dl>


<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_get\_error\_message() {#gae09912101ce40de1049e5bf6355f6137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * lto_get_error_message (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the last error string or NULL if last operation was successful.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_get\_version() {#gabea4fdb81db6b16bd57b5da06cb5b5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_C_EXTERN_C_BEGIN const char * lto_get_version (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a printable string.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_initialize\_disassembler() {#gac16cae88f84b9eb72f1fbbe31a0f90da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_initialize_disassembler (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes LLVM disassemblers.</p>


<p>FIXME: This doesn't really belong here.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=5</p></dd>
</dl>


<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_input\_create() {#gad18583a45953ea42efd18ab773cda9a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_input_t lto_input_create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * buffer, size_t buffer_size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates an LTO input file from a buffer.</p>


<p>The path argument is used for diagnotics as this function otherwise does not know which file the given buffer is associated with.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=24</p></dd>
</dl>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_input\_dispose() {#ga048da4fd05807227a91a907f8563aa5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_input_dispose (<a href="#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a> input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Frees all memory internally allocated by the LTO input file.</p>


<p>Upon return the <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> is no longer valid.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=24</p></dd>
</dl>


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_input\_get\_dependent\_library() {#gaf4e64e6d599e7d40b3c05a169def0bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * lto_input_get_dependent_library (<a href="#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a> input, size_t index, size_t * size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the ith dependent library specifier for the given LTO input file.</p>


<p>The returned string is not null-terminated.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=24</p></dd>
</dl>


<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### lto\_input\_get\_num\_dependent\_libraries() {#ga23a95dfd07fbb9f9180b1866be4faba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned lto_input_get_num_dependent_libraries (<a href="#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a> input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of dependent library specifiers for the given LTO input file.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=24</p></dd>
</dl>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create() {#ga2bce26a37f3a58f5966c327e984e13c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file from disk.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_from\_fd() {#ga584067ea7910e54e01147d01a7a9cba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_from_fd (int fd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path, size_t file_size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file from disk.</p>


<p>The seek point of fd is not preserved. Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=5</p></dd>
</dl>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_from\_fd\_at\_offset() {#gaf414c81bc3bb9b7e890bd4f19ee16a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_from_fd_at_offset (int fd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path, size_t file_size, size_t map_size, off_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file from disk.</p>


<p>The seek point of fd is not preserved. Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=5</p></dd>
</dl>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_from\_memory() {#ga64f951ad0a065f54861970bdf1f8c3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_from_memory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file from memory.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_from\_memory\_with\_path() {#ga9e33f0d18f0736afce91d3ed98132384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_from_memory_with_path (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file from memory with an extra path argument.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=9</p></dd>
</dl>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_in\_codegen\_context() {#ga05d6a2cd667124de281532624ea6ba8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_in_codegen_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path, <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file in the codegen context.</p>


<p>Loads an object file into the same context as <span class="doxyComputerOutput">cg</span>. The module is safe to add using <em><a href="#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module()</a></em>.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=11</p></dd>
</dl>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_create\_in\_local\_context() {#ga1da5dff4e86f96d4521f8a4aebe079e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_module_t lto_module_create_in_local_context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads an object file in its own context.</p>


<p>Loads an object file in its own LLVMContext. This function call is thread-safe. However, modules created this way should not be merged into an <a href="#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> using <em><a href="#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module()</a></em>.</p>


<p>Returns NULL on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=11</p></dd>
</dl>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_dispose() {#gafea8ec5886536824e8b654a113601917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_module_dispose (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Frees all memory internally allocated by the module.</p>


<p>Upon return the <a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> is no longer valid.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_linkeropts() {#ga5bab2de970d06f8fa7b4c56f8e384161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * lto_module_get_linkeropts (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the module's linker options.</p>


<p>The linker options may consist of multiple flags. It is the linker's responsibility to split the flags using a platform-specific mechanism.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=16</p></dd>
</dl>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_macho\_cputype() {#ga16718eb3a64b14d3fc6ebdaf119e5875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_get_macho_cputype (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod, unsigned int * out_cputype, unsigned int * out_cpusubtype)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If targeting mach-o on darwin, this function gets the CPU type and subtype that will end up being encoded in the mach-o header.</p>


<p>These are the values that can be found in mach/machine.h.</p>


<p><span class="doxyComputerOutput">out_cputype</span> and <span class="doxyComputerOutput">out_cpusubtype</span> must be non-NULL.</p>


<p>Returns true on error (check <a href="#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=27</p></dd>
</dl>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_num\_symbols() {#ga5a1e077d0ac49bae8a1329a772906998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int lto_module_get_num_symbols (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of symbols in the object module.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_symbol\_attribute() {#ga91598116ef3f8f7772211ed6a85a91b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_symbol_attributes lto_module_get_symbol_attribute (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod, unsigned int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the attributes of the ith symbol in the object module.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_symbol\_name() {#ga9adf61162416e60f69bd5165651fa378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * lto_module_get_symbol_name (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod, unsigned int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the name of the ith symbol in the object module.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_get\_target\_triple() {#ga332b4c1bacc474567f2a474ddef3ae62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * lto_module_get_target_triple (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns triple string which the object module was compiled under.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_has\_ctor\_dtor() {#ga5b59ee17299706db881f30ad4ea8e1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_has_ctor_dtor (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function can be used by the linker to check if a given module has any constructor or destructor functions.</p>


<p>Returns true if the module has either the @llvm.global_ctors or the @llvm.global_dtors symbol. Otherwise returns false.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=29</p></dd>
</dl>


<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_has\_objc\_category() {#ga8e393ebb821c5013502483d55c9f990b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_has_objc_category (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">Buffer</span> contains a bitcode file with ObjC code (category or class) in it.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=20</p></dd>
</dl>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_is\_object\_file() {#gae07005b7262f934bccb0d13e29ea12a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_is_object_file (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if a file is a loadable object file.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_is\_object\_file\_for\_target() {#gaae8cb3eaf287d255af45ae7a745dcf5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_is_object_file_for_target (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * target_triple_prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if a file is a loadable object compiled for requested target.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_is\_object\_file\_in\_memory() {#gaca136d5490410db13e79001020f711df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_is_object_file_in_memory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if a buffer is a loadable object file.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_is\_object\_file\_in\_memory\_for\_target() {#gaa57ab02868d4736b7d5ea5a3c0faacaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_is_object_file_in_memory_for_target (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * mem, size_t length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * target_triple_prefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if a buffer is a loadable object compiled for requested target.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=3</p></dd>
</dl>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_module\_set\_target\_triple() {#ga35e37587fda0ee1e4e90db17956c22f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_module_set_target_triple (<a href="#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * triple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets triple string with which the object will be codegened.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=4</p></dd>
</dl>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### lto\_runtime\_lib\_symbols\_list() {#ga2221e1ea6d3053c540ccd3eb078ab749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const  * lto_runtime_lib_symbols_list (size_t * size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the list of libcall symbols that can be generated by LTO that might not be visible from the symbol table of bitcode files.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>prior to LTO_API_VERSION=25</p></dd>
</dl>


<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### lto\_set\_debug\_options() {#ga1e1f6473e0c498f3562c655355e45374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lto_set_debug_options (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * options, int number)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses options immediately, making them available as early as possible.</p>


<p>For example during executing codegen::InitTargetOptionsFromCodeGenFlags. Since parsing shud only happen once, only one of lto_codegen_debug_options or lto_set_debug_options should be called.</p>


<p>This function takes one or more options separated by spaces. Warning: passing file paths through this function may confuse the argument parser if the paths contain spaces.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=28</p></dd>
</dl>


<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LTO\_API\_VERSION {#ga7cd7eb9fdade49e998bef7b80ea6c0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LTO_API_VERSION&nbsp;&nbsp;&nbsp;29</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
