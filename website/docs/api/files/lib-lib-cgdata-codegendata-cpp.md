---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/cgdata/codegendata-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CodeGenData.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">llvm/CGData/CodeGenDataReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">llvm/CGData/OutlinedHashTreeRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmaprecord-h">llvm/CGData/StableFunctionMapRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/caching-h">llvm/Support/Caching.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "llvm/CGData/CodeGenData.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegendata-cpp-">anonymous{CodeGenData.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/indexedcgdata">IndexedCGData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/cgdata">cgdata</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegendata-cpp-/cgdataerrorcategorytype">CGDataErrorCategoryType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2467dd4bd3f2da739d104b355ed6d362">getCGDataErrString</a> (cgdata_error Err, const std::string &amp;ErrMsg="")</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb94a17c6e0104702ff3c8fd9fab8f2">CodeGenDataGenerate</a>("codegen-data-generate", cl::init(false), cl::Hidden, cl::desc("Emit CodeGen Data into custom sections"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7851e11614b6c08d4326e58b2ec744">CodeGenDataUsePath</a>("codegen-data-use-path", cl::init(""), cl::Hidden, cl::desc("File path to where .cgdata file is read"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477832f90e9c98e1d9c574aa7a599d62">CodeGenDataThinLTOTwoRounds</a>("codegen-data-thinlto-two-rounds", cl::init(false), cl::Hidden, cl::desc("Enable two-round ThinLTO code generation. The first round " "emits codegen data, while the second round uses the emitted " "codegen data for further optimizations."))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"cg-data"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b97a1d3b66aae039e7fa8516f5dcf8">CG_DATA_SECT_ENTRY</a>(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;  SectNameCommon,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484a5e8d454838ed60c22cb6f5612fad">CG_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_outline</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_merge</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55dc8171a7674baeadcb3a4736cdbbae">CG_DATA_OUTLINE_COFF</a>&nbsp;&nbsp;&nbsp;".loutline"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add273b3d8474ec87c05db2cea27be460">CG_DATA_MERGE_COFF</a>&nbsp;&nbsp;&nbsp;".lmerge"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07502d4c25b7a4f01918b9ca167fc96">CG_DATA_OUTLINE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01254ac1c006af0d72af52ad629c797b">CG_DATA_MERGE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd6594c5dfa62b6b3b239efc0de3d01">CG_DATA_INDEX_VERSION</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b22a8683c1fbb322cec3f5b62aab24">CG_DATA_SECT_ENTRY</a>(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;  SectNameCoff,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd0957428f97844ca9998faaf048f50">CG_DATA_SIMPLE_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c059f3bc28296b2214d017a72b0b94">CG_DATA_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b97bb254e362d7e73d12734e778516">CG_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3655b73d93cb40beb940cac945ccd132">CG_DATA_OUTLINE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_outline</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1784a54b9744352d33bd217afb4847f">CG_DATA_MERGE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_merge</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2b88551b7326787b2c4da8ed175ec6">CG_DATA_OUTLINE_COFF</a>&nbsp;&nbsp;&nbsp;".loutline"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a48b9573477752cf6436b3fbd08ca76">CG_DATA_MERGE_COFF</a>&nbsp;&nbsp;&nbsp;".lmerge"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b76bb2ab5d7542697f21386cfb250f9">CG_DATA_OUTLINE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c58e8d24daacdaa94affa4f48c5a854">CG_DATA_MERGE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a6a20ca5474eeb301558224978ee3e">CG_DATA_INDEX_VERSION</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003e82c4d72462b86c230e6b2250b8ff">CG_DATA_SECT_ENTRY</a>(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;Prefix,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2e2d794c59ae60f81d7d127c95f649">CG_DATA_SIMPLE_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280582bf165f44edcf400b5bcdc8fec3">CG_DATA_QUOTE</a>(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d90849c2d27efae239f80ef465d150b">CG_DATA_DEFINED</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87735314ed49adc5e25061d092622f70">CG_DATA_OUTLINE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_outline</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36cea4185a74a612ec4ace1ba5cb476c">CG_DATA_MERGE_COMMON</a>&nbsp;&nbsp;&nbsp;__llvm_merge</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b5fd99e3f7425c798f6a96a86d8feb3">CG_DATA_OUTLINE_COFF</a>&nbsp;&nbsp;&nbsp;".loutline"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21048b15c87265314504df0decb4789">CG_DATA_MERGE_COFF</a>&nbsp;&nbsp;&nbsp;".lmerge"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29fc7fe1934cb9f78a99c973999ff3db">CG_DATA_OUTLINE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e5781e1482738402133e5d640f73de">CG_DATA_MERGE_SECT_NAME</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd13881a7ad5d221cc5a048ca7e31b3">CG_DATA_INDEX_VERSION</a>&nbsp;&nbsp;&nbsp;2</td>
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

## Functions

### getCGDataErrString() {#a2467dd4bd3f2da739d104b355ed6d362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getCGDataErrString (<a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96">cgdata_error</a> Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; ErrMsg="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96adde571add68cc36593098a17df48bd45">llvm::bad_header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a35ca84a2e9411227c0819d26eed0ce2c">llvm::bad_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a7fa280f7e48ee78c16e6ceec49532736">llvm::empty_cgdata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a2e51b1ab42e8a4a67f3445174be5191b">llvm::eof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a2af01f2c39c66a1641045dd660e839b5">llvm::unsupported_version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cgdataerror/#aa43a450f77d79dde035d8f5213adab48">llvm::CGDataError::message</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CodeGenDataGenerate {#a7cb94a17c6e0104702ff3c8fd9fab8f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; CodeGenDataGenerate("codegen-data-generate", cl::init(false), cl::Hidden, cl::desc("Emit CodeGen Data into custom sections"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>.</p>

</div>
</div>

### CodeGenDataThinLTOTwoRounds {#a477832f90e9c98e1d9c574aa7a599d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; CodeGenDataThinLTOTwoRounds("codegen-data-thinlto-two-rounds", cl::init(false), cl::Hidden, cl::desc("Enable two-round ThinLTO code generation. The first round " "emits codegen data, while the second round uses the emitted " "codegen data for further optimizations."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>.</p>

</div>
</div>

### CodeGenDataUsePath {#a6a7851e11614b6c08d4326e58b2ec744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; CodeGenDataUsePath("codegen-data-use-path", cl::init(""), cl::Hidden, cl::desc("File path to where .cgdata file is read"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CG\_DATA\_DEFINED {#a484a5e8d454838ed60c22cb6f5612fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_DEFINED {#a20b97bb254e362d7e73d12734e778516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_DEFINED {#a8d90849c2d27efae239f80ef465d150b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_DEFINED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_INDEX\_VERSION {#a8bd6594c5dfa62b6b3b239efc0de3d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_INDEX_VERSION&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_INDEX\_VERSION {#a24a6a20ca5474eeb301558224978ee3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_INDEX_VERSION&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_INDEX\_VERSION {#a6fd13881a7ad5d221cc5a048ca7e31b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_INDEX_VERSION&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COFF {#add273b3d8474ec87c05db2cea27be460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COFF&nbsp;&nbsp;&nbsp;".lmerge"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COFF {#a4a48b9573477752cf6436b3fbd08ca76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COFF&nbsp;&nbsp;&nbsp;".lmerge"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COFF {#ab21048b15c87265314504df0decb4789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COFF&nbsp;&nbsp;&nbsp;".lmerge"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COMMON {#a9194077710db2d0b68bc9f1ec299c7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COMMON&nbsp;&nbsp;&nbsp;__llvm_merge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COMMON {#aa1784a54b9744352d33bd217afb4847f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COMMON&nbsp;&nbsp;&nbsp;__llvm_merge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_COMMON {#a36cea4185a74a612ec4ace1ba5cb476c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_COMMON&nbsp;&nbsp;&nbsp;__llvm_merge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_SECT\_NAME {#a01254ac1c006af0d72af52ad629c797b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_SECT\_NAME {#a3c58e8d24daacdaa94affa4f48c5a854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_MERGE\_SECT\_NAME {#ae5e5781e1482738402133e5d640f73de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_MERGE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9194077710db2d0b68bc9f1ec299c7fb">CG_DATA_MERGE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COFF {#a55dc8171a7674baeadcb3a4736cdbbae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COFF&nbsp;&nbsp;&nbsp;".loutline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COFF {#a6b2b88551b7326787b2c4da8ed175ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COFF&nbsp;&nbsp;&nbsp;".loutline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COFF {#a6b5fd99e3f7425c798f6a96a86d8feb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COFF&nbsp;&nbsp;&nbsp;".loutline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COMMON {#a895a7cd01d120f313080055b9ba67e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COMMON&nbsp;&nbsp;&nbsp;__llvm_outline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COMMON {#a3655b73d93cb40beb940cac945ccd132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COMMON&nbsp;&nbsp;&nbsp;__llvm_outline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_COMMON {#a87735314ed49adc5e25061d092622f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_COMMON&nbsp;&nbsp;&nbsp;__llvm_outline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_SECT\_NAME {#ad07502d4c25b7a4f01918b9ca167fc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_SECT\_NAME {#a7b76bb2ab5d7542697f21386cfb250f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_OUTLINE\_SECT\_NAME {#a29fc7fe1934cb9f78a99c973999ff3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_OUTLINE_SECT_NAME&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a9e44402ece363a1354b3452084e62c30">CG_DATA_QUOTE</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a895a7cd01d120f313080055b9ba67e09">CG_DATA_OUTLINE_COMMON</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_QUOTE {#a9e44402ece363a1354b3452084e62c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_QUOTE(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_QUOTE {#a96c059f3bc28296b2214d017a72b0b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_QUOTE(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_QUOTE {#a280582bf165f44edcf400b5bcdc8fec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_QUOTE(x)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h/#a5afeb7e80292c5659c959a76c690a516">CG_DATA_SIMPLE_QUOTE</a>(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_SECT\_ENTRY {#a63b97a1d3b66aae039e7fa8516f5dcf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SECT_ENTRY(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;  SectNameCommon,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>

</div>
</div>

### CG\_DATA\_SECT\_ENTRY {#a07b22a8683c1fbb322cec3f5b62aab24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SECT_ENTRY(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;  SectNameCoff,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>

</div>
</div>

### CG\_DATA\_SECT\_ENTRY {#a003e82c4d72462b86c230e6b2250b8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SECT_ENTRY(Kind, SectNameCommon, SectNameCoff, Prefix)&nbsp;&nbsp;&nbsp;Prefix,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>

</div>
</div>

### CG\_DATA\_SIMPLE\_QUOTE {#a5afeb7e80292c5659c959a76c690a516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SIMPLE_QUOTE(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_SIMPLE\_QUOTE {#a3cd0957428f97844ca9998faaf048f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SIMPLE_QUOTE(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file CodeGenData.inc.</p>

</div>
</div>

### CG\_DATA\_SIMPLE\_QUOTE {#a7d2e2d794c59ae60f81d7d127c95f649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CG_DATA_SIMPLE_QUOTE(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file CodeGenData.inc.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"cg-data"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
