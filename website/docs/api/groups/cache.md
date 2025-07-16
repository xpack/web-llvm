---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/cache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The controlling options Reference

<p>These entry points control the ThinLTO cache. <a href="#details">More...</a></p>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/thinltocodegenerator/cachingoptions">CachingOptions</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga13ac54ea2d670ae2b55c55d552ae2d2d">setCacheDir</a> (std::string Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a path to a directory where to store the cached files for incremental build. <a href="#ga13ac54ea2d670ae2b55c55d552ae2d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga190f2d73ac70288b5323a0881fa0c727">setCachePruningInterval</a> (int Interval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: interval (seconds) between two prunes of the cache. <a href="#ga190f2d73ac70288b5323a0881fa0c727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5ba128cec363595b8cb8d403509b71d7">setCacheEntryExpiration</a> (unsigned Expiration)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: expiration (in seconds) for an entry. <a href="#ga5ba128cec363595b8cb8d403509b71d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga724a34dbf10eb5f09062e52237ea0e96">setMaxCacheSizeRelativeToAvailableSpace</a> (unsigned Percentage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk. <a href="#ga724a34dbf10eb5f09062e52237ea0e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga755ef880ddfb2ecdf8b5cae2d611dd78">setCacheMaxSizeBytes</a> (uint64_t MaxSizeBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: the maximum size for the cache directory in bytes. <a href="#ga755ef880ddfb2ecdf8b5cae2d611dd78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaca3298ccd1bd11e22a2119a0868177b4">setCacheMaxSizeFiles</a> (unsigned MaxSizeFiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: the maximum number of files in the cache directory. <a href="#gaca3298ccd1bd11e22a2119a0868177b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>These entry points control the ThinLTO cache.</p>


<p>The cache is intended to support incremental build, and thus needs to be persistent accross build. The client enabled the cache by supplying a path to an existing directory. The code generator will use this to store objects files that may be reused during a subsequent build. To avoid filling the disk space, a few knobs are provided:</p>


<ul class="doxyList ">
<li>The pruning interval limit the frequency at which the garbage collector will try to scan the cache directory to prune it from expired entries. Setting to -1 disable the pruning (default). Setting to 0 will force pruning to occur.</li>
<li>The pruning expiration time indicates to the garbage collector how old an entry needs to be to be removed.</li>
<li>Finally, the garbage collector can be instructed to prune the cache till the occupied space goes below a threshold.</li>
</ul>

<div class="doxySectionDef">

## Functions

### setCacheDir() {#ga13ac54ea2d670ae2b55c55d552ae2d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setCacheDir (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a path to a directory where to store the cached files for incremental build.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCacheEntryExpiration() {#ga5ba128cec363595b8cb8d403509b71d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setCacheEntryExpiration (unsigned Expiration)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache policy: expiration (in seconds) for an entry.</p>


<p>A value of 0 will be ignored.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCacheMaxSizeBytes() {#ga755ef880ddfb2ecdf8b5cae2d611dd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setCacheMaxSizeBytes (uint64_t MaxSizeBytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache policy: the maximum size for the cache directory in bytes.</p>


<p>A value over the amount of available space on the disk will be reduced to the amount of available space. A value of 0 will be ignored.</p>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCacheMaxSizeFiles() {#gaca3298ccd1bd11e22a2119a0868177b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setCacheMaxSizeFiles (unsigned MaxSizeFiles)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache policy: the maximum number of files in the cache directory.</p>


<p>A value of 0 will be ignored.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCachePruningInterval() {#ga190f2d73ac70288b5323a0881fa0c727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setCachePruningInterval (int Interval)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache policy: interval (seconds) between two prunes of the cache.</p>


<p>Set to a negative value to disable pruning. A value of 0 will force pruning to occur.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### setMaxCacheSizeRelativeToAvailableSpace() {#ga724a34dbf10eb5f09062e52237ea0e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThinLTOCodeGenerator::setMaxCacheSizeRelativeToAvailableSpace (unsigned Percentage)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk.</p>


<p>Set to 100 to indicate no limit, 50 to indicate that the cache size will not be left over half the available space. A value over 100 will be reduced to 100, and a value of 0 will be ignored.</p>


<p>The formula looks like: AvailableSpace = FreeSpace + ExistingCacheSize NewCacheSize = AvailableSpace * P/100</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
