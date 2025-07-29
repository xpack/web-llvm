---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/lto-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `lto.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h">llvm-c/ExternC.h</a>"
#include &lt;stddef.h&gt;
#include &lt;sys/types.h&gt;
#include &lt;stdbool.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/ltoobjectbuffer">LTOObjectBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Type to wrap a single object returned by ThinLTO. <a href="/web-llvm/docs/api/structs/ltoobjectbuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">bool <a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOModule * <a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a loaded object module <a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOCodeGenerator * <a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a code generator <a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueThinLTOCodeGenerator * <a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque reference to a thin code generator <a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="/web-llvm/docs/api/groups/llvmclto/#gacc8bcb5e44e35ed3a8b8e9f077218c21">lto_diagnostic_handler_t</a>)(lto_codegen_diagnostic_severity_t severity, const char *diag, void *ctxt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic handler type. <a href="/web-llvm/docs/api/groups/llvmclto/#gacc8bcb5e44e35ed3a8b8e9f077218c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueLTOInput * <a href="/web-llvm/docs/api/groups/llvmclto/#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opaque reference to an LTO input file. <a href="/web-llvm/docs/api/groups/llvmclto/#gaa6aff1636eea0cf605498fa8cdd100e0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_symbol_attributes { <a href="/web-llvm/docs/api/groups/llvmclto/#ga913b51e895306793f1c843f1385d6d77">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_debug_model { <a href="/web-llvm/docs/api/groups/llvmclto/#ga45b08530a7582678cb4c03bc70a33bae">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_codegen_model { <a href="/web-llvm/docs/api/groups/llvmclto/#gad17a28f0ff971d0c201f4716b25948a4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">lto_codegen_diagnostic_severity_t { <a href="/web-llvm/docs/api/groups/llvmclto/#ga7d1dffbb71e58b376fc879b8098957b3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic severity. <a href="/web-llvm/docs/api/groups/llvmclto/#ga7d1dffbb71e58b376fc879b8098957b3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gabea4fdb81db6b16bd57b5da06cb5b5ba">lto_get_version</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a printable string. <a href="/web-llvm/docs/api/groups/llvmclto/#gabea4fdb81db6b16bd57b5da06cb5b5ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last error string or NULL if last operation was successful. <a href="/web-llvm/docs/api/groups/llvmclto/#gae09912101ce40de1049e5bf6355f6137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gae07005b7262f934bccb0d13e29ea12a0">lto_module_is_object_file</a> (const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a file is a loadable object file. <a href="/web-llvm/docs/api/groups/llvmclto/#gae07005b7262f934bccb0d13e29ea12a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaae8cb3eaf287d255af45ae7a745dcf5b">lto_module_is_object_file_for_target</a> (const char *path, const char *target_triple_prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a file is a loadable object compiled for requested target. <a href="/web-llvm/docs/api/groups/llvmclto/#gaae8cb3eaf287d255af45ae7a745dcf5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga8e393ebb821c5013502483d55c9f990b">lto_module_has_objc_category</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Buffer</span> contains a bitcode file with ObjC code (category or class) in it. <a href="/web-llvm/docs/api/groups/llvmclto/#ga8e393ebb821c5013502483d55c9f990b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaca136d5490410db13e79001020f711df">lto_module_is_object_file_in_memory</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a buffer is a loadable object file. <a href="/web-llvm/docs/api/groups/llvmclto/#gaca136d5490410db13e79001020f711df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaa57ab02868d4736b7d5ea5a3c0faacaa">lto_module_is_object_file_in_memory_for_target</a> (const void *mem, size_t length, const char *target_triple_prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if a buffer is a loadable object compiled for requested target. <a href="/web-llvm/docs/api/groups/llvmclto/#gaa57ab02868d4736b7d5ea5a3c0faacaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga2bce26a37f3a58f5966c327e984e13c2">lto_module_create</a> (const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="/web-llvm/docs/api/groups/llvmclto/#ga2bce26a37f3a58f5966c327e984e13c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga64f951ad0a065f54861970bdf1f8c3fc">lto_module_create_from_memory</a> (const void *mem, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from memory. <a href="/web-llvm/docs/api/groups/llvmclto/#ga64f951ad0a065f54861970bdf1f8c3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga9e33f0d18f0736afce91d3ed98132384">lto_module_create_from_memory_with_path</a> (const void *mem, size_t length, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from memory with an extra path argument. <a href="/web-llvm/docs/api/groups/llvmclto/#ga9e33f0d18f0736afce91d3ed98132384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga1da5dff4e86f96d4521f8a4aebe079e7">lto_module_create_in_local_context</a> (const void *mem, size_t length, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file in its own context. <a href="/web-llvm/docs/api/groups/llvmclto/#ga1da5dff4e86f96d4521f8a4aebe079e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga05d6a2cd667124de281532624ea6ba8c">lto_module_create_in_codegen_context</a> (const void *mem, size_t length, const char *path, lto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file in the codegen context. <a href="/web-llvm/docs/api/groups/llvmclto/#ga05d6a2cd667124de281532624ea6ba8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga584067ea7910e54e01147d01a7a9cba3">lto_module_create_from_fd</a> (int fd, const char *path, size_t file_size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="/web-llvm/docs/api/groups/llvmclto/#ga584067ea7910e54e01147d01a7a9cba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaf414c81bc3bb9b7e890bd4f19ee16a93">lto_module_create_from_fd_at_offset</a> (int fd, const char *path, size_t file_size, size_t map_size, off_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads an object file from disk. <a href="/web-llvm/docs/api/groups/llvmclto/#gaf414c81bc3bb9b7e890bd4f19ee16a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gafea8ec5886536824e8b654a113601917">lto_module_dispose</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all memory internally allocated by the module. <a href="/web-llvm/docs/api/groups/llvmclto/#gafea8ec5886536824e8b654a113601917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga332b4c1bacc474567f2a474ddef3ae62">lto_module_get_target_triple</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns triple string which the object module was compiled under. <a href="/web-llvm/docs/api/groups/llvmclto/#ga332b4c1bacc474567f2a474ddef3ae62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga35e37587fda0ee1e4e90db17956c22f5">lto_module_set_target_triple</a> (lto_module_t mod, const char *triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets triple string with which the object will be codegened. <a href="/web-llvm/docs/api/groups/llvmclto/#ga35e37587fda0ee1e4e90db17956c22f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga5a1e077d0ac49bae8a1329a772906998">lto_module_get_num_symbols</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of symbols in the object module. <a href="/web-llvm/docs/api/groups/llvmclto/#ga5a1e077d0ac49bae8a1329a772906998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga9adf61162416e60f69bd5165651fa378">lto_module_get_symbol_name</a> (lto_module_t mod, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the ith symbol in the object module. <a href="/web-llvm/docs/api/groups/llvmclto/#ga9adf61162416e60f69bd5165651fa378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga913b51e895306793f1c843f1385d6d77">lto_symbol_attributes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga91598116ef3f8f7772211ed6a85a91b4">lto_module_get_symbol_attribute</a> (lto_module_t mod, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the attributes of the ith symbol in the object module. <a href="/web-llvm/docs/api/groups/llvmclto/#ga91598116ef3f8f7772211ed6a85a91b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga5bab2de970d06f8fa7b4c56f8e384161">lto_module_get_linkeropts</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module's linker options. <a href="/web-llvm/docs/api/groups/llvmclto/#ga5bab2de970d06f8fa7b4c56f8e384161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga16718eb3a64b14d3fc6ebdaf119e5875">lto_module_get_macho_cputype</a> (lto_module_t mod, unsigned int *out_cputype, unsigned int *out_cpusubtype)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If targeting mach-o on darwin, this function gets the CPU type and subtype that will end up being encoded in the mach-o header. <a href="/web-llvm/docs/api/groups/llvmclto/#ga16718eb3a64b14d3fc6ebdaf119e5875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga5b59ee17299706db881f30ad4ea8e1ee">lto_module_has_ctor_dtor</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function can be used by the linker to check if a given module has any constructor or destructor functions. <a href="/web-llvm/docs/api/groups/llvmclto/#ga5b59ee17299706db881f30ad4ea8e1ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga9f570562a736b80813cba9ae10ace299">lto_codegen_set_diagnostic_handler</a> (lto_code_gen_t, lto_diagnostic_handler_t, void *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a diagnostic handler and the related context (void *). <a href="/web-llvm/docs/api/groups/llvmclto/#ga9f570562a736b80813cba9ae10ace299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga31b1a72b22fc9dcca1ecd28c92e3f89d">lto_codegen_create</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiates a code generator. <a href="/web-llvm/docs/api/groups/llvmclto/#ga31b1a72b22fc9dcca1ecd28c92e3f89d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga0751ca93aa0745e38238d1907ef749a1">lto_codegen_create_in_local_context</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiate a code generator in its own context. <a href="/web-llvm/docs/api/groups/llvmclto/#ga0751ca93aa0745e38238d1907ef749a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga226045782babbda624255217e4934dae">lto_codegen_dispose</a> (lto_code_gen_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all code generator and all memory it internally allocated. <a href="/web-llvm/docs/api/groups/llvmclto/#ga226045782babbda624255217e4934dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaca40f093d4adbb3dcc24fe7f0056684d">lto_codegen_add_module</a> (lto_code_gen_t cg, lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an object module to the set of modules for which code will be generated. <a href="/web-llvm/docs/api/groups/llvmclto/#gaca40f093d4adbb3dcc24fe7f0056684d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga92adb73abd04aa8c1a3223edc161b4bf">lto_codegen_set_module</a> (lto_code_gen_t cg, lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the object module for code generation. <a href="/web-llvm/docs/api/groups/llvmclto/#ga92adb73abd04aa8c1a3223edc161b4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gad42e2035d7309b212f66dd61c17ffed0">lto_codegen_set_debug_model</a> (lto_code_gen_t cg, lto_debug_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets if debug info should be generated. <a href="/web-llvm/docs/api/groups/llvmclto/#gad42e2035d7309b212f66dd61c17ffed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga77f96a4bf050ec91cca0830107ed815b">lto_codegen_set_pic_model</a> (lto_code_gen_t cg, lto_codegen_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets which PIC code model to generated. <a href="/web-llvm/docs/api/groups/llvmclto/#ga77f96a4bf050ec91cca0830107ed815b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gae396c8c812ab4d06c76520234be6ce94">lto_codegen_set_cpu</a> (lto_code_gen_t cg, const char *cpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cpu to generate code for. <a href="/web-llvm/docs/api/groups/llvmclto/#gae396c8c812ab4d06c76520234be6ce94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gafee8bbe13e5a24fe6f05bf9e34f5365a">lto_codegen_set_assembler_path</a> (lto_code_gen_t cg, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the location of the assembler tool to run. <a href="/web-llvm/docs/api/groups/llvmclto/#gafee8bbe13e5a24fe6f05bf9e34f5365a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga26548a5c0df7b8c3b642637442449b8f">lto_codegen_set_assembler_args</a> (lto_code_gen_t cg, const char **args, int nargs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets extra arguments that libLTO should pass to the assembler. <a href="/web-llvm/docs/api/groups/llvmclto/#ga26548a5c0df7b8c3b642637442449b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gac2b8b7c3f5322c232e269c93f4377d70">lto_codegen_add_must_preserve_symbol</a> (lto_code_gen_t cg, const char *symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds to a list of all global symbols that must exist in the final generated code. <a href="/web-llvm/docs/api/groups/llvmclto/#gac2b8b7c3f5322c232e269c93f4377d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga430254fbb8e2da52467fca97173879d8">lto_codegen_write_merged_modules</a> (lto_code_gen_t cg, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a new object file at the specified path that contains the merged contents of all modules added so far. <a href="/web-llvm/docs/api/groups/llvmclto/#ga430254fbb8e2da52467fca97173879d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga2046c9820e71ce99f76234359be8df73">lto_codegen_compile</a> (lto_code_gen_t cg, size_t *length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for all added modules into one native object file. <a href="/web-llvm/docs/api/groups/llvmclto/#ga2046c9820e71ce99f76234359be8df73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gadfde0ad97850e1479009556404f5bc61">lto_codegen_compile_to_file</a> (lto_code_gen_t cg, const char **name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for all added modules into one native object file. <a href="/web-llvm/docs/api/groups/llvmclto/#gadfde0ad97850e1479009556404f5bc61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaadfca2f414f452b73109c99438c71351">lto_codegen_optimize</a> (lto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs optimization for the merged module. <a href="/web-llvm/docs/api/groups/llvmclto/#gaadfca2f414f452b73109c99438c71351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gad07286ee88f734bf57437c9c0f7d4c6a">lto_codegen_compile_optimized</a> (lto_code_gen_t cg, size_t *length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code for the optimized merged module into one native object file. <a href="/web-llvm/docs/api/groups/llvmclto/#gad07286ee88f734bf57437c9c0f7d4c6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga9022709cbee7447810418cdbbe66d081">lto_api_version</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the runtime API version. <a href="/web-llvm/docs/api/groups/llvmclto/#ga9022709cbee7447810418cdbbe66d081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga1e1f6473e0c498f3562c655355e45374">lto_set_debug_options</a> (const char *const *options, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses options immediately, making them available as early as possible. <a href="/web-llvm/docs/api/groups/llvmclto/#ga1e1f6473e0c498f3562c655355e45374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga05ff9b7bf60f4b42ce3f54dd10f12d11">lto_codegen_debug_options</a> (lto_code_gen_t cg, const char *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets options to help debug codegen bugs. <a href="/web-llvm/docs/api/groups/llvmclto/#ga05ff9b7bf60f4b42ce3f54dd10f12d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gafb79ab57d848388bea55173ebd9e16ef">lto_codegen_debug_options_array</a> (lto_code_gen_t cg, const char *const *, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as the previous function, but takes every option separately through an array. <a href="/web-llvm/docs/api/groups/llvmclto/#gafb79ab57d848388bea55173ebd9e16ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gac16cae88f84b9eb72f1fbbe31a0f90da">lto_initialize_disassembler</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes LLVM disassemblers. <a href="/web-llvm/docs/api/groups/llvmclto/#gac16cae88f84b9eb72f1fbbe31a0f90da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga7d0a764a39bdf298b43a75590c4a4073">lto_codegen_set_should_internalize</a> (lto_code_gen_t cg, lto_bool_t ShouldInternalize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets if we should run internalize pass during optimization and code generation. <a href="/web-llvm/docs/api/groups/llvmclto/#ga7d0a764a39bdf298b43a75590c4a4073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga1f857dd87f6159db003e7c12c40466ce">lto_codegen_set_should_embed_uselists</a> (lto_code_gen_t cg, lto_bool_t ShouldEmbedUselists)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to embed uselists in bitcode. <a href="/web-llvm/docs/api/groups/llvmclto/#ga1f857dd87f6159db003e7c12c40466ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaa6aff1636eea0cf605498fa8cdd100e0">lto_input_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gad18583a45953ea42efd18ab773cda9a0">lto_input_create</a> (const void *buffer, size_t buffer_size, const char *path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an LTO input file from a buffer. <a href="/web-llvm/docs/api/groups/llvmclto/#gad18583a45953ea42efd18ab773cda9a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga048da4fd05807227a91a907f8563aa5f">lto_input_dispose</a> (lto_input_t input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees all memory internally allocated by the LTO input file. <a href="/web-llvm/docs/api/groups/llvmclto/#ga048da4fd05807227a91a907f8563aa5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga23a95dfd07fbb9f9180b1866be4faba5">lto_input_get_num_dependent_libraries</a> (lto_input_t input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of dependent library specifiers for the given LTO input file. <a href="/web-llvm/docs/api/groups/llvmclto/#ga23a95dfd07fbb9f9180b1866be4faba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaf4e64e6d599e7d40b3c05a169def0bdb">lto_input_get_dependent_library</a> (lto_input_t input, size_t index, size_t *size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ith dependent library specifier for the given LTO input file. <a href="/web-llvm/docs/api/groups/llvmclto/#gaf4e64e6d599e7d40b3c05a169def0bdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga2221e1ea6d3053c540ccd3eb078ab749">lto_runtime_lib_symbols_list</a> (size_t *size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of libcall symbols that can be generated by LTO that might not be visible from the symbol table of bitcode files. <a href="/web-llvm/docs/api/groups/llvmclto/#ga2221e1ea6d3053c540ccd3eb078ab749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga8ed1f0fc73822da5f1d749dffa8d8071">thinlto_create_codegen</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiates a ThinLTO code generator. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga8ed1f0fc73822da5f1d749dffa8d8071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gafa8eb4c3e5fa635e51c92a913fc19aca">thinlto_codegen_dispose</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees the generator and all memory it internally allocated. <a href="/web-llvm/docs/api/groups/llvmctlto/#gafa8eb4c3e5fa635e51c92a913fc19aca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gaa9e95873812d6c95eaed4669f5a8e218">thinlto_codegen_add_module</a> (thinlto_code_gen_t cg, const char *identifier, const char *data, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module to a ThinLTO code generator. <a href="/web-llvm/docs/api/groups/llvmctlto/#gaa9e95873812d6c95eaed4669f5a8e218">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gac2ddec507ad62cf885d333152a80bd9f">thinlto_codegen_process</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize and codegen all the modules added to the codegenerator using ThinLTO. <a href="/web-llvm/docs/api/groups/llvmctlto/#gac2ddec507ad62cf885d333152a80bd9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga4b0d79fbe2182463fd0a8549669f661d">thinlto_module_get_num_objects</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of object files produced by the ThinLTO CodeGenerator. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga4b0d79fbe2182463fd0a8549669f661d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/ltoobjectbuffer">LTOObjectBuffer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga55822450a0ed1d0c2706c9bf194adb63">thinlto_module_get_object</a> (thinlto_code_gen_t cg, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the ith object file produced by the ThinLTO CodeGenerator. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga55822450a0ed1d0c2706c9bf194adb63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gab2701c474a2e855b522647d4403bc735">thinlto_module_get_num_object_files</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of object files produced by the ThinLTO CodeGenerator. <a href="/web-llvm/docs/api/groups/llvmctlto/#gab2701c474a2e855b522647d4403bc735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga6a623a3136782e9ae1a4b168c8231b67">thinlto_module_get_object_file</a> (thinlto_code_gen_t cg, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the path to the ith object file produced by the ThinLTO CodeGenerator. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga6a623a3136782e9ae1a4b168c8231b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga1bdfd6ec585a2b80fbaef4d1c7d3141e">thinlto_codegen_set_pic_model</a> (thinlto_code_gen_t cg, lto_codegen_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets which PIC code model to generate. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga1bdfd6ec585a2b80fbaef4d1c7d3141e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga3ec329f8acd2712922566a82b84ed896">thinlto_codegen_set_savetemps_dir</a> (thinlto_code_gen_t cg, const char *save_temps_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the path to a directory to use as a storage for temporary bitcode files. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga3ec329f8acd2712922566a82b84ed896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga6fd04a0b513b9eb915d5bc33a4a51945">thinlto_set_generated_objects_dir</a> (thinlto_code_gen_t cg, const char *save_temps_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the path to a directory where to save generated object files. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga6fd04a0b513b9eb915d5bc33a4a51945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga88be70959374f7c525b310713abe574d">thinlto_codegen_set_cpu</a> (thinlto_code_gen_t cg, const char *cpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cpu to generate code for. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga88be70959374f7c525b310713abe574d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga22eabf983805c0999e0a9f76ac4fe38f">thinlto_codegen_disable_codegen</a> (thinlto_code_gen_t cg, lto_bool_t disable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable CodeGen, only run the stages till codegen and stop. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga22eabf983805c0999e0a9f76ac4fe38f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gad4ac940c874be5090130f2b93ebe99ea">thinlto_codegen_set_codegen_only</a> (thinlto_code_gen_t cg, lto_bool_t codegen_only)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform CodeGen only: disable all other stages. <a href="/web-llvm/docs/api/groups/llvmctlto/#gad4ac940c874be5090130f2b93ebe99ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga26b2637e824b47093a7ef6987c3854a3">thinlto_debug_options</a> (const char *const *options, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse -mllvm style debug options. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga26b2637e824b47093a7ef6987c3854a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gab4ebc07d5540166b4aeedfbbd2720757">lto_module_is_thinlto</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if a module has support for ThinLTO linking. <a href="/web-llvm/docs/api/groups/llvmctlto/#gab4ebc07d5540166b4aeedfbbd2720757">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#gaac473108a947da1a6b02d8bb32d50e23">thinlto_codegen_add_must_preserve_symbol</a> (thinlto_code_gen_t cg, const char *name, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a symbol to the list of global symbols that must exist in the final generated code. <a href="/web-llvm/docs/api/groups/llvmctlto/#gaac473108a947da1a6b02d8bb32d50e23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto/#ga04d8f6924e666ac75b707c5159935056">thinlto_codegen_add_cross_referenced_symbol</a> (thinlto_code_gen_t cg, const char *name, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a symbol to the list of global symbols that are cross-referenced between ThinLTO files. <a href="/web-llvm/docs/api/groups/llvmctlto/#ga04d8f6924e666ac75b707c5159935056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga6ec37b4d07f9ca12a6dd7c425ea32f97">thinlto_codegen_set_cache_dir</a> (thinlto_code_gen_t cg, const char *cache_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the path to a directory to use as a cache storage for incremental build. <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga6ec37b4d07f9ca12a6dd7c425ea32f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga8cb942810ce430321ec21e8621536b2e">thinlto_codegen_set_cache_pruning_interval</a> (thinlto_code_gen_t cg, int interval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cache pruning interval (in seconds). <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga8cb942810ce430321ec21e8621536b2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga296083b17c0cb3c208659235c166dc10">thinlto_codegen_set_final_cache_size_relative_to_available_space</a> (thinlto_code_gen_t cg, unsigned percentage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk. <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga296083b17c0cb3c208659235c166dc10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga9d6b04c106df48580e3b59fdfb38ca03">thinlto_codegen_set_cache_entry_expiration</a> (thinlto_code_gen_t cg, unsigned expiration)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the expiration (in seconds) for an entry in the cache. <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga9d6b04c106df48580e3b59fdfb38ca03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga87a51042c5bb698ec9a3704baacbdef8">thinlto_codegen_set_cache_size_bytes</a> (thinlto_code_gen_t cg, unsigned max_size_bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum size of the cache directory (in bytes). <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga87a51042c5bb698ec9a3704baacbdef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga017444e811c5736d4266fe97dc3a2969">thinlto_codegen_set_cache_size_megabytes</a> (thinlto_code_gen_t cg, unsigned max_size_megabytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as thinlto_codegen_set_cache_size_bytes, except the maximum size is in megabytes (2^20 bytes). <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga017444e811c5736d4266fe97dc3a2969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga46aff02588486d19399de795b8747877">thinlto_codegen_set_cache_size_files</a> (thinlto_code_gen_t cg, unsigned max_size_files)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum number of files in the cache directory. <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#ga46aff02588486d19399de795b8747877">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#ga7cd7eb9fdade49e998bef7b80ea6c0e4">LTO_API_VERSION</a>&nbsp;&nbsp;&nbsp;29</td>
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

### lto\_bool\_t {#a1f863f3727405a63300a2eaab9719e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef bool lto_bool_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
