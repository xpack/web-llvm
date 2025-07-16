---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmctlto
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The ThinLTO Reference

<p>// endgoup LLVMCLTO <a href="#details">More...</a></p>

## Topics Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctlto-caching">ThinLTO Cache Control</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>// endgoup LLVMCTLTO <a href="/web-llvm/docs/api/groups/llvmctlto-caching/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8ed1f0fc73822da5f1d749dffa8d8071">thinlto_create_codegen</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiates a ThinLTO code generator. <a href="#ga8ed1f0fc73822da5f1d749dffa8d8071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafa8eb4c3e5fa635e51c92a913fc19aca">thinlto_codegen_dispose</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frees the generator and all memory it internally allocated. <a href="#gafa8eb4c3e5fa635e51c92a913fc19aca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa9e95873812d6c95eaed4669f5a8e218">thinlto_codegen_add_module</a> (thinlto_code_gen_t cg, const char *identifier, const char *data, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module to a ThinLTO code generator. <a href="#gaa9e95873812d6c95eaed4669f5a8e218">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac2ddec507ad62cf885d333152a80bd9f">thinlto_codegen_process</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize and codegen all the modules added to the codegenerator using ThinLTO. <a href="#gac2ddec507ad62cf885d333152a80bd9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4b0d79fbe2182463fd0a8549669f661d">thinlto_module_get_num_objects</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of object files produced by the ThinLTO CodeGenerator. <a href="#ga4b0d79fbe2182463fd0a8549669f661d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/ltoobjectbuffer">LTOObjectBuffer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga55822450a0ed1d0c2706c9bf194adb63">thinlto_module_get_object</a> (thinlto_code_gen_t cg, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the ith object file produced by the ThinLTO CodeGenerator. <a href="#ga55822450a0ed1d0c2706c9bf194adb63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab2701c474a2e855b522647d4403bc735">thinlto_module_get_num_object_files</a> (thinlto_code_gen_t cg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of object files produced by the ThinLTO CodeGenerator. <a href="#gab2701c474a2e855b522647d4403bc735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6a623a3136782e9ae1a4b168c8231b67">thinlto_module_get_object_file</a> (thinlto_code_gen_t cg, unsigned int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the path to the ith object file produced by the ThinLTO CodeGenerator. <a href="#ga6a623a3136782e9ae1a4b168c8231b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1bdfd6ec585a2b80fbaef4d1c7d3141e">thinlto_codegen_set_pic_model</a> (thinlto_code_gen_t cg, lto_codegen_model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets which PIC code model to generate. <a href="#ga1bdfd6ec585a2b80fbaef4d1c7d3141e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3ec329f8acd2712922566a82b84ed896">thinlto_codegen_set_savetemps_dir</a> (thinlto_code_gen_t cg, const char *save_temps_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the path to a directory to use as a storage for temporary bitcode files. <a href="#ga3ec329f8acd2712922566a82b84ed896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6fd04a0b513b9eb915d5bc33a4a51945">thinlto_set_generated_objects_dir</a> (thinlto_code_gen_t cg, const char *save_temps_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the path to a directory where to save generated object files. <a href="#ga6fd04a0b513b9eb915d5bc33a4a51945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga88be70959374f7c525b310713abe574d">thinlto_codegen_set_cpu</a> (thinlto_code_gen_t cg, const char *cpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cpu to generate code for. <a href="#ga88be70959374f7c525b310713abe574d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga22eabf983805c0999e0a9f76ac4fe38f">thinlto_codegen_disable_codegen</a> (thinlto_code_gen_t cg, lto_bool_t disable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable CodeGen, only run the stages till codegen and stop. <a href="#ga22eabf983805c0999e0a9f76ac4fe38f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad4ac940c874be5090130f2b93ebe99ea">thinlto_codegen_set_codegen_only</a> (thinlto_code_gen_t cg, lto_bool_t codegen_only)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform CodeGen only: disable all other stages. <a href="#gad4ac940c874be5090130f2b93ebe99ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga26b2637e824b47093a7ef6987c3854a3">thinlto_debug_options</a> (const char *const *options, int number)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse -mllvm style debug options. <a href="#ga26b2637e824b47093a7ef6987c3854a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab4ebc07d5540166b4aeedfbbd2720757">lto_module_is_thinlto</a> (lto_module_t mod)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if a module has support for ThinLTO linking. <a href="#gab4ebc07d5540166b4aeedfbbd2720757">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaac473108a947da1a6b02d8bb32d50e23">thinlto_codegen_add_must_preserve_symbol</a> (thinlto_code_gen_t cg, const char *name, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a symbol to the list of global symbols that must exist in the final generated code. <a href="#gaac473108a947da1a6b02d8bb32d50e23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga04d8f6924e666ac75b707c5159935056">thinlto_codegen_add_cross_referenced_symbol</a> (thinlto_code_gen_t cg, const char *name, int length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a symbol to the list of global symbols that are cross-referenced between ThinLTO files. <a href="#ga04d8f6924e666ac75b707c5159935056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>// endgoup LLVMCLTO</p>

<div class="doxySectionDef">

## Functions

### lto\_module\_is\_thinlto() {#gab4ebc07d5540166b4aeedfbbd2720757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t lto_module_is_thinlto (<a href="/web-llvm/docs/api/groups/llvmclto/#ga3ce415fd9e8109d4835461c6de1b9d82">lto_module_t</a> mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if a module has support for ThinLTO linking.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_add\_cross\_referenced\_symbol() {#ga04d8f6924e666ac75b707c5159935056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_add_cross_referenced_symbol (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name, int length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a symbol to the list of global symbols that are cross-referenced between ThinLTO files.</p>


<p>If the ThinLTO CodeGenerator can ensure that every references from a ThinLTO module to this symbol is optimized away, then the symbol can be discarded.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### thinlto\_codegen\_add\_module() {#gaa9e95873812d6c95eaed4669f5a8e218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_add_module (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * identifier, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * data, int length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a module to a ThinLTO code generator.</p>


<p>Identifier has to be unique among all the modules in a code generator. The data buffer stays owned by the client, and is expected to be available for the entire lifetime of the <a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> it is added to.</p>


<p>On failure, returns NULL (check <a href="/web-llvm/docs/api/groups/llvmclto/#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>

</div>
</div>

### thinlto\_codegen\_add\_must\_preserve\_symbol() {#gaac473108a947da1a6b02d8bb32d50e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_add_must_preserve_symbol (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name, int length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a symbol to the list of global symbols that must exist in the final generated code.</p>


<p>If a function is not listed there, it might be inlined into every usage and optimized away. For every single module, the functions referenced from code outside of the ThinLTO modules need to be added here.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### thinlto\_codegen\_disable\_codegen() {#ga22eabf983805c0999e0a9f76ac4fe38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_disable_codegen (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a> disable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable CodeGen, only run the stages till codegen and stop.</p>


<p>The output will be bitcode.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=19</p></dd>
</dl>


<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_dispose() {#gafa8eb4c3e5fa635e51c92a913fc19aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_dispose (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Frees the generator and all memory it internally allocated.</p>


<p>Upon return the <a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> is no longer valid.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_process() {#gac2ddec507ad62cf885d333152a80bd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_process (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize and codegen all the modules added to the codegenerator using ThinLTO.</p>


<p>Resulting objects are accessible using <a href="#ga55822450a0ed1d0c2706c9bf194adb63">thinlto_module_get_object()</a>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_codegen\_only() {#gad4ac940c874be5090130f2b93ebe99ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_codegen_only (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h/#a1f863f3727405a63300a2eaab9719e7a">lto_bool_t</a> codegen_only)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform CodeGen only: disable all other stages.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=19</p></dd>
</dl>


<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cpu() {#ga88be70959374f7c525b310713abe574d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cpu (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * cpu)</td>
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
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_pic\_model() {#ga1bdfd6ec585a2b80fbaef4d1c7d3141e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_bool_t thinlto_codegen_set_pic_model (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/groups/llvmclto/#gad17a28f0ff971d0c201f4716b25948a4">lto_codegen_model</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets which PIC code model to generate.</p>


<p>Returns true on error (check <a href="/web-llvm/docs/api/groups/llvmclto/#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_savetemps\_dir() {#ga3ec329f8acd2712922566a82b84ed896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_savetemps_dir (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * save_temps_dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the path to a directory to use as a storage for temporary bitcode files.</p>


<p>The intention is to make the bitcode files available for debugging at various stage of the pipeline.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_create\_codegen() {#ga8ed1f0fc73822da5f1d749dffa8d8071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">thinlto_code_gen_t thinlto_create_codegen (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instantiates a ThinLTO code generator.</p>


<p>Returns NULL on error (check <a href="/web-llvm/docs/api/groups/llvmclto/#gae09912101ce40de1049e5bf6355f6137">lto_get_error_message()</a> for details).</p>


<p>The ThinLTOCodeGenerator is not intended to be reuse for multiple compilation: the model is that the client adds modules to the generator and ask to perform the ThinLTO optimizations / codegen, and finally destroys the codegenerator.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_debug\_options() {#ga26b2637e824b47093a7ef6987c3854a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_debug_options (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * options, int number)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse -mllvm style debug options.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_module\_get\_num\_object\_files() {#gab2701c474a2e855b522647d4403bc735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int thinlto_module_get_num_object_files (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of object files produced by the ThinLTO CodeGenerator.</p>


<p>It usually matches the number of input files, but this is not a guarantee of the API and may change in future implementation, so the client should not assume it.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=21</p></dd>
</dl>


<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_module\_get\_num\_objects() {#ga4b0d79fbe2182463fd0a8549669f661d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int thinlto_module_get_num_objects (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of object files produced by the ThinLTO CodeGenerator.</p>


<p>It usually matches the number of input files, but this is not a guarantee of the API and may change in future implementation, so the client should not assume it.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_module\_get\_object() {#ga55822450a0ed1d0c2706c9bf194adb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTOObjectBuffer thinlto_module_get_object (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a reference to the ith object file produced by the ThinLTO CodeGenerator.</p>


<p>Client should use <span class="doxyComputerOutput"><a href="#ga4b0d79fbe2182463fd0a8549669f661d">thinlto_module_get_num_objects()</a></span> to get the number of available objects.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_module\_get\_object\_file() {#ga6a623a3136782e9ae1a4b168c8231b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * thinlto_module_get_object_file (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the path to the ith object file produced by the ThinLTO CodeGenerator.</p>


<p>Client should use <span class="doxyComputerOutput"><a href="#gab2701c474a2e855b522647d4403bc735">thinlto_module_get_num_object_files()</a></span> to get the number of available objects.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=21</p></dd>
</dl>


<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_set\_generated\_objects\_dir() {#ga6fd04a0b513b9eb915d5bc33a4a51945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_set_generated_objects_dir (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * save_temps_dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the path to a directory where to save generated object files.</p>


<p>This path can be used by a linker to request on-disk files instead of in-memory buffers. When set, results are available through <a href="#ga6a623a3136782e9ae1a4b168c8231b67">thinlto_module_get_object_file()</a> instead of <a href="#ga55822450a0ed1d0c2706c9bf194adb63">thinlto_module_get_object()</a>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=21</p></dd>
</dl>


<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
