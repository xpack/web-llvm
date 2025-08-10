---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmctlto-caching
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# ThinLTO Cache Control

<p>// endgoup LLVMCTLTO <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6ec37b4d07f9ca12a6dd7c425ea32f97">thinlto_codegen_set_cache_dir</a> (thinlto_code_gen_t cg, const char *cache_dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the path to a directory to use as a cache storage for incremental build. <a href="#ga6ec37b4d07f9ca12a6dd7c425ea32f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8cb942810ce430321ec21e8621536b2e">thinlto_codegen_set_cache_pruning_interval</a> (thinlto_code_gen_t cg, int interval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the cache pruning interval (in seconds). <a href="#ga8cb942810ce430321ec21e8621536b2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga296083b17c0cb3c208659235c166dc10">thinlto_codegen_set_final_cache_size_relative_to_available_space</a> (thinlto_code_gen_t cg, unsigned percentage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk. <a href="#ga296083b17c0cb3c208659235c166dc10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9d6b04c106df48580e3b59fdfb38ca03">thinlto_codegen_set_cache_entry_expiration</a> (thinlto_code_gen_t cg, unsigned expiration)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the expiration (in seconds) for an entry in the cache. <a href="#ga9d6b04c106df48580e3b59fdfb38ca03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga87a51042c5bb698ec9a3704baacbdef8">thinlto_codegen_set_cache_size_bytes</a> (thinlto_code_gen_t cg, unsigned max_size_bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum size of the cache directory (in bytes). <a href="#ga87a51042c5bb698ec9a3704baacbdef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga017444e811c5736d4266fe97dc3a2969">thinlto_codegen_set_cache_size_megabytes</a> (thinlto_code_gen_t cg, unsigned max_size_megabytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as thinlto_codegen_set_cache_size_bytes, except the maximum size is in megabytes (2^20 bytes). <a href="#ga017444e811c5736d4266fe97dc3a2969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga46aff02588486d19399de795b8747877">thinlto_codegen_set_cache_size_files</a> (thinlto_code_gen_t cg, unsigned max_size_files)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum number of files in the cache directory. <a href="#ga46aff02588486d19399de795b8747877">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>// endgoup LLVMCTLTO</p>


<p>These entry points control the ThinLTO cache. The cache is intended to support incremental builds, and thus needs to be persistent across builds. The client enables the cache by supplying a path to an existing directory. The code generator will use this to store objects files that may be reused during a subsequent build. To avoid filling the disk space, a few knobs are provided:</p>


<ul class="doxyList ">
<li>The pruning interval limits the frequency at which the garbage collector will try to scan the cache directory to prune expired entries. Setting to a negative number disables the pruning.</li>
<li>The pruning expiration time indicates to the garbage collector how old an entry needs to be to be removed.</li>
<li>Finally, the garbage collector can be instructed to prune the cache until the occupied space goes below a threshold.</li>
</ul>

<div class="doxySectionDef">

## Functions

### thinlto\_codegen\_set\_cache\_dir() {#ga6ec37b4d07f9ca12a6dd7c425ea32f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_dir (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * cache_dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the path to a directory to use as a cache storage for incremental build.</p>


<p>Setting this activates caching.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cache\_entry\_expiration() {#ga9d6b04c106df48580e3b59fdfb38ca03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_entry_expiration (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned expiration)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the expiration (in seconds) for an entry in the cache.</p>


<p>An unspecified default value will be applied. A value of 0 will be ignored.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cache\_pruning\_interval() {#ga8cb942810ce430321ec21e8621536b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_pruning_interval (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, int interval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the cache pruning interval (in seconds).</p>


<p>A negative value disables the pruning. An unspecified default value will be applied, and a value of 0 will force prunning to occur.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cache\_size\_bytes() {#ga87a51042c5bb698ec9a3704baacbdef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_size_bytes (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned max_size_bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the maximum size of the cache directory (in bytes).</p>


<p>A value over the amount of available space on the disk will be reduced to the amount of available space. An unspecified default value will be applied. A value of 0 will be ignored.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=22</p></dd>
</dl>


<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cache\_size\_files() {#ga46aff02588486d19399de795b8747877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_size_files (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned max_size_files)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the maximum number of files in the cache directory.</p>


<p>An unspecified default value will be applied. A value of 0 will be ignored.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=22</p></dd>
</dl>


<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#ae016a3733553fe3990c8dfcec10d9d3a">LLVM_C_EXTERN_C_END</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_cache\_size\_megabytes() {#ga017444e811c5736d4266fe97dc3a2969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_cache_size_megabytes (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned max_size_megabytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as thinlto_codegen_set_cache_size_bytes, except the maximum size is in megabytes (2^20 bytes).</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=23</p></dd>
</dl>


<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

### thinlto\_codegen\_set\_final\_cache\_size\_relative\_to\_available\_space() {#ga296083b17c0cb3c208659235c166dc10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void thinlto_codegen_set_final_cache_size_relative_to_available_space (<a href="/web-llvm/docs/api/groups/llvmclto/#gaad92d29c62685dde82e298596453c415">thinlto_code_gen_t</a> cg, unsigned percentage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk.</p>


<p>Set to 100 to indicate no limit, 50 to indicate that the cache size will not be left over half the available space. A value over 100 will be reduced to 100, a value of 0 will be ignored. An unspecified default value will be applied.</p>


<p>The formula looks like: AvailableSpace = FreeSpace + ExistingCacheSize NewCacheSize = AvailableSpace * P/100</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>LTO_API_VERSION=18</p></dd>
</dl>


<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lto-h">lto.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
