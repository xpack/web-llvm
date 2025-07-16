---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/localcxxruntimeoverridesbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LocalCXXRuntimeOverridesBase` Class Reference

<p>Support class for static dtor execution. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::LocalCXXRuntimeOverridesBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">llvm/ExecutionEngine/Orc/ExecutionUtils.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/localcxxruntimeoverrides">LocalCXXRuntimeOverrides</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea138afefeb12981d4216d5afcc4f1d">DestructorPtr</a> = void(*)(void *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5603c98eee50419372982078eb77d9">CXXDestructorDataPair</a> = std::pair&lt; <a href="#a2ea138afefeb12981d4216d5afcc4f1d">DestructorPtr</a>, void * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98da520b28f7630edbd8d5985786b4a7">CXXDestructorDataPairList</a> = std::vector&lt; <a href="#aef5603c98eee50419372982078eb77d9">CXXDestructorDataPair</a> &gt;</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6660e6f3ac5389aff5f76aca3d986b6">runDestructors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run any destructors recorded by the overriden __cxa_atexit function (CXAAtExitOverride). <a href="#af6660e6f3ac5389aff5f76aca3d986b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98da520b28f7630edbd8d5985786b4a7">CXXDestructorDataPairList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5477cfeb6c50bd9f23c6cfceac3742">DSOHandleOverride</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cc84e2b76f2afd9e616e835dac8159">CXAAtExitOverride</a> (DestructorPtr Destructor, void *Arg, void *DSOHandle)</td>
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

## Description {#details}

<p>Support class for static dtor execution.</p>


<p>For hosted (in-process) JITs only!</p>


<p>If a __cxa_atexit function isn't found C++ programs that use static destructors will fail to link. However, we don't want to use the host process's __cxa_atexit, because it will schedule JIT'd destructors to run after the JIT has been torn down, which is no good. This class makes it easy to override __cxa_atexit (and the related __dso_handle).</p>


<p>To use, clients should manually call searchOverrides from their symbol resolver. This should generally be done after attempting symbol resolution inside the JIT, but before searching the host process's symbol table. When the client determines that destructors should be run (generally at JIT teardown or after a return from main), the runDestructors method should be called.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### CXXDestructorDataPair {#aef5603c98eee50419372982078eb77d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LocalCXXRuntimeOverridesBase::CXXDestructorDataPair =  std::pair&lt;DestructorPtr, void *&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### CXXDestructorDataPairList {#a98da520b28f7630edbd8d5985786b4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LocalCXXRuntimeOverridesBase::CXXDestructorDataPairList =  std::vector&lt;CXXDestructorDataPair&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### DestructorPtr {#a2ea138afefeb12981d4216d5afcc4f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LocalCXXRuntimeOverridesBase::DestructorPtr =  void (*)(void *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runDestructors() {#af6660e6f3ac5389aff5f76aca3d986b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LocalCXXRuntimeOverridesBase::runDestructors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run any destructors recorded by the overriden __cxa_atexit function (CXAAtExitOverride).</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="#abd5477cfeb6c50bd9f23c6cfceac3742">DSOHandleOverride</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DSOHandleOverride {#abd5477cfeb6c50bd9f23c6cfceac3742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CXXDestructorDataPairList llvm::orc::LocalCXXRuntimeOverridesBase::DSOHandleOverride</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/localcxxruntimeoverrides/#a64281bb2737cb8f10abe3b3ec40d23c4">llvm::orc::LocalCXXRuntimeOverrides::enable</a> and <a href="#af6660e6f3ac5389aff5f76aca3d986b6">runDestructors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### CXAAtExitOverride() {#a54cc84e2b76f2afd9e616e835dac8159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::orc::LocalCXXRuntimeOverridesBase::CXAAtExitOverride (<a href="#a2ea138afefeb12981d4216d5afcc4f1d">DestructorPtr</a> Destructor, void * Arg, void * DSOHandle)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/localcxxruntimeoverrides/#a64281bb2737cb8f10abe3b3ec40d23c4">llvm::orc::LocalCXXRuntimeOverrides::enable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
