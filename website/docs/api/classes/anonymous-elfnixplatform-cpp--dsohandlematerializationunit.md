---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elfnixplatform-cpp-/dsohandlematerializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DSOHandleMaterializationUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517e8b3a196c8ae3af7c297f059081fd">DSOHandleMaterializationUnit</a> (ELFNixPlatform &amp;ENP, const SymbolStringPtr &amp;DSOHandleSymbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1bff1a2553c0bf0d3acec582592679">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of this materialization unit. <a href="#a5a1bff1a2553c0bf0d3acec582592679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fea932231dc6a48267f7317163c3d7b">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#a6fea932231dc6a48267f7317163c3d7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b0f1503f6a7f152379990de504168b3">discard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Sym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#a1b0f1503f6a7f152379990de504168b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebaa0a7dc10074e37775ccb44e067fc">getDSOHandleContent</a> (size_t PointerSize)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3417fed64265c3e6185d69d3f05bde">ENP</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4e43188423a2a5d707643815182f31">createDSOHandleSectionInterface</a> (ELFNixPlatform &amp;ENP, const SymbolStringPtr &amp;DSOHandleSymbol)</td>
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


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DSOHandleMaterializationUnit() {#a517e8b3a196c8ae3af7c297f059081fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::DSOHandleMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp; ENP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; DSOHandleSymbol)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1233ea2ef51205e4954cdc12e7bc2d81">llvm::orc::MaterializationUnit::MaterializationUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### discard() {#a1b0f1503f6a7f152379990de504168b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
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


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a235f764fe0f700836f89667ef5a0033b">llvm::orc::MaterializationUnit::JITDylib</a>.</p>

</div>
</div>

### getName() {#a5a1bff1a2553c0bf0d3acec582592679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::getName ()</td>
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


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### materialize() {#a6fea932231dc6a48267f7317163c3d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
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

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda7a1920d61156abc05a60135aefe8bc67">llvm::jitlink::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562">llvm::jitlink::aarch64::Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/loongarch/#a7be3e7f350a78822211e1c660f34cc3eac293043e113515d2a9cf442d7863c5b1">llvm::jitlink::loongarch::Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c">llvm::jitlink::ppc64::Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">llvm::jitlink::x86_64::Pointer64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fac43e0fd449c758dab8f891d8e19eb1a9">llvm::jitlink::Strong</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getDSOHandleContent() {#aaebaa0a7dc10074e37775ccb44e067fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::getDSOHandleContent (size_t PointerSize)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ENP {#a3f3417fed64265c3e6185d69d3f05bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFNixPlatform&amp; anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::ENP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createDSOHandleSectionInterface() {#a5a4e43188423a2a5d707643815182f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializationUnit::Interface anonymous{ELFNixPlatform.cpp}::DSOHandleMaterializationUnit::createDSOHandleSectionInterface (<a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp; ENP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; DSOHandleSymbol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

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
