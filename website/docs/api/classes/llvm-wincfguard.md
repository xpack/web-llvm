---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/wincfguard
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WinCFGuard` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WinCFGuard { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">CodeGen/AsmPrinter/WinCFGuard.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler">AsmPrinterHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects and handles <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> objects required to build debug or EH information. <a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d0b47e336ca75d0919ad4463ceb553">WinCFGuard</a> (AsmPrinter *A)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98438e11c66be4ae18b8f5c2cd159b9">~WinCFGuard</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bbf914eeb964dd21e71c6b0b77410e">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the Control Flow Guard function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> table. <a href="#a94bbf914eeb964dd21e71c6b0b77410e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c86dc68138a524306a1e5b5f341805">beginFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function debug information. <a href="#a20c86dc68138a524306a1e5b5f341805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44f251bf25dc7412804917d12ff2cdf">endFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather post-function debug information. <a href="#ac44f251bf25dc7412804917d12ff2cdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05091d0323deff5169afafc65940fdfc">lookupImpSymbol</a> (const MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9687184b3ab059353c24f91af137a924">Asm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of directive emission. <a href="#a9687184b3ab059353c24f91af137a924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f10978e0b8c4fc1befcdde9d6c21b1">LongjmpTargets</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WinCFGuard() {#a09d0b47e336ca75d0919ad4463ceb553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinCFGuard::WinCFGuard (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp">WinCFGuard.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WinCFGuard() {#ad98438e11c66be4ae18b8f5c2cd159b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinCFGuard::~WinCFGuard ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>.</p>


<p>Reference <a href="#a94bbf914eeb964dd21e71c6b0b77410e">endModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginFunction() {#a20c86dc68138a524306a1e5b5f341805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::WinCFGuard::beginFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather pre-function debug information.</p>


<p>Every beginFunction(MF) call should be followed by an endFunction(MF) call.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>.</p>

</div>
</div>

### endFunction() {#ac44f251bf25dc7412804917d12ff2cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCFGuard::endFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather post-function debug information.</p>


<p>Please note that some <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> implementations may not call beginFunction at all.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp">WinCFGuard.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3ec107b1f5caf6f3d790d36f2808305">llvm::MachineFunction::getLongjmpTargets</a>.</p>

</div>
</div>

### endModule() {#a94bbf914eeb964dd21e71c6b0b77410e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCFGuard::endModule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the Control Flow Guard function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> table.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp">WinCFGuard.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp/#aaf4331210de8ead749895971e5de9791">isPossibleIndirectCallTarget</a>.</p>


<p>Referenced by <a href="#ad98438e11c66be4ae18b8f5c2cd159b9">~WinCFGuard</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### lookupImpSymbol() {#a05091d0323deff5169afafc65940fdfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * WinCFGuard::lookupImpSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp">WinCFGuard.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Asm {#a9687184b3ab059353c24f91af137a924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::WinCFGuard::Asm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of directive emission.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>.</p>

</div>
</div>

### LongjmpTargets {#af3f10978e0b8c4fc1befcdde9d6c21b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const MCSymbol *&gt; llvm::WinCFGuard::LongjmpTargets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-cpp">WinCFGuard.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wincfguard-h">WinCFGuard.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
