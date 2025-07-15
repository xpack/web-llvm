---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFNixPlatformCompleteBootstrapMaterializationUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> represents a set of symbol definitions that can be materialized as a group, or individually discarded (when overriding definitions are encountered). <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d86f46ab83f3ab13b0276437b6e7783">ELFNixPlatformCompleteBootstrapMaterializationUnit</a> (ELFNixPlatform &amp;MOP, StringRef PlatformJDName, SymbolStringPtr CompleteBootstrapSymbol, DeferredRuntimeFnMap DeferredAAs, ExecutorAddr ELFNixHeaderAddr, ExecutorAddr PlatformBootstrap, ExecutorAddr PlatformShutdown, ExecutorAddr RegisterJITDylib, ExecutorAddr DeregisterJITDylib)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696affbfbc3bddc05c8bbc9830e02b33">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of this materialization unit. <a href="#a696affbfbc3bddc05c8bbc9830e02b33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18b5e663aa3f2116768bde792d2df6f">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#aa18b5e663aa3f2116768bde792d2df6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7539ff05ec4033c095ff06e83ef4fa25">discard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Sym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#a7539ff05ec4033c095ff06e83ef4fa25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7135321c5ff9e9f87d7be5b8f21cb9">MOP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d33b5ee52f87ce3f9d7b4152c229a13">PlatformJDName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac346bd7151858f2f85421ef01294e064">CompleteBootstrapSymbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a89d08c06a4587d638d75c2d4fcf4b54c">DeferredRuntimeFnMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ab54eabe09c4b9c2a7ebd273c2c24d">DeferredAAsMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab752d54aae241f57982386fa8e25347b">ELFNixHeaderAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45921c5ee902976fd2e37f4a05a24cb1">PlatformBootstrap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0746c4a6b35d0356514af029c939f7e">PlatformShutdown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27af176c6d4e1be0ce32d479ec02071">RegisterJITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5b8b1bfbfffd03974c7f64f8b860cb">DeregisterJITDylib</a></td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFNixPlatformCompleteBootstrapMaterializationUnit() {#a3d86f46ab83f3ab13b0276437b6e7783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::ELFNixPlatformCompleteBootstrapMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp; MOP, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PlatformJDName, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> CompleteBootstrapSymbol, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a89d08c06a4587d638d75c2d4fcf4b54c">DeferredRuntimeFnMap</a> DeferredAAs, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ELFNixHeaderAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> PlatformBootstrap, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> PlatformShutdown, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> RegisterJITDylib, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> DeregisterJITDylib)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1233ea2ef51205e4954cdc12e7bc2d81">llvm::orc::MaterializationUnit::MaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">llvm::JITSymbolFlags::None</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### discard() {#a7539ff05ec4033c095ff06e83ef4fa25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementations of this method should discard the given symbol from the source (e.g.</p>


<p>if the source is an LLVM IR Module and the symbol is a function, delete the function body or mark it available externally).</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a235f764fe0f700836f89667ef5a0033b">llvm::orc::MaterializationUnit::JITDylib</a>.</p>

</div>
</div>

### getName() {#a696affbfbc3bddc05c8bbc9830e02b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of this materialization unit.</p>


<p>Useful for debugging output.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### materialize() {#aa18b5e663aa3f2116768bde792d2df6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#ac924edcd8ad4ceeebcbcea4ca04a793b">llvm::orc::shared::WrapperFunctionCall::Create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfnixplatform-cpp-/#a4edaac18b04b42252a7c922e21fcc222">anonymous{ELFNixPlatform.cpp}::createPlatformGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CompleteBootstrapSymbol {#ac346bd7151858f2f85421ef01294e064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::CompleteBootstrapSymbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### DeferredAAsMap {#a42ab54eabe09c4b9c2a7ebd273c2c24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeferredRuntimeFnMap anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::DeferredAAsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### DeregisterJITDylib {#aef5b8b1bfbfffd03974c7f64f8b860cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::DeregisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### ELFNixHeaderAddr {#ab752d54aae241f57982386fa8e25347b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::ELFNixHeaderAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### MOP {#a8b7135321c5ff9e9f87d7be5b8f21cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFNixPlatform&amp; anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::MOP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### PlatformBootstrap {#a45921c5ee902976fd2e37f4a05a24cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::PlatformBootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### PlatformJDName {#a5d33b5ee52f87ce3f9d7b4152c229a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::PlatformJDName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### PlatformShutdown {#ad0746c4a6b35d0356514af029c939f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::PlatformShutdown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### RegisterJITDylib {#ac27af176c6d4e1be0ce32d479ec02071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::RegisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
