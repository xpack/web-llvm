---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86MCCodeEmitter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> - Generic instruction encoding interface. <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a91a4b7ba7dadf46425e8bbb463e5f">X86MCCodeEmitter</a> (const MCInstrInfo &amp;mcii, MCContext &amp;ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d03bfbb5ef9339d763877e8eed11e1e">X86MCCodeEmitter</a> (const X86MCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a9b636f13b82da7f22637018777935">~X86MCCodeEmitter</a> () override=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter">X86MCCodeEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699a1d43432a5ce0bbdaa90f3c3e9d21">operator=</a> (const X86MCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380773ba72f8745ffdea347917d48a95">emitPrefix</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a326c8dcef7365124098e7573ebe4bd31">encodeInstruction</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>. <a href="#a326c8dcef7365124098e7573ebe4bd31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c2bf2c1fc729d5f86009f36533a6b5">getX86RegNum</a> (const MCOperand &amp;MO) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bdd5cc5c04afe9c994f2f2c234ac68">getX86RegEncoding</a> (const MCInst &amp;MI, unsigned OpNum) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f5eebb5cb136ccfeb2e1a4cad662df">emitImmediate</a> (const MCOperand &amp;Disp, SMLoc Loc, unsigned ImmSize, MCFixupKind FixupKind, uint64_t StartByte, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, int ImmOffset=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ed27aef5b41f919a88ccfcc3291af2">emitRegModRMByte</a> (const MCOperand &amp;ModRMReg, unsigned RegOpcodeFld, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d7243a5b6afc8efbd07e7eb0f52eae">emitSIBByte</a> (unsigned SS, unsigned Index, unsigned Base, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d824fdec9e34e27bb3710ede2400e1">emitMemModRMByte</a> (const MCInst &amp;MI, unsigned Op, unsigned RegOpcodeField, uint64_t TSFlags, PrefixKind Kind, uint64_t StartByte, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI, bool ForceSIB=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#aae2e4a2445610ae8ab1d4aba35ad36b7">PrefixKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927873c0d6057171e1ca4d83ceb000cd">emitPrefixImpl</a> (unsigned &amp;CurOp, const MCInst &amp;MI, const MCSubtargetInfo &amp;STI, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all instruction prefixes. <a href="#a927873c0d6057171e1ca4d83ceb000cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#aae2e4a2445610ae8ab1d4aba35ad36b7">PrefixKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c6075fcce68f7258885e1228ce5332">emitVEXOpcodePrefix</a> (int MemOperand, const MCInst &amp;MI, const MCSubtargetInfo &amp;STI, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit XOP, VEX2, VEX3 or EVEX prefix. <a href="#a72c6075fcce68f7258885e1228ce5332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab5979a635c31462c9e9f398d862d34">emitSegmentOverridePrefix</a> (unsigned SegOperand, const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit segment override opcode prefix as needed. <a href="#a5ab5979a635c31462c9e9f398d862d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#aae2e4a2445610ae8ab1d4aba35ad36b7">PrefixKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0380d1619a4fdac78ae5bfa7f2b68832">emitOpcodePrefix</a> (int MemOperand, const MCInst &amp;MI, const MCSubtargetInfo &amp;STI, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all instruction prefixes prior to the opcode. <a href="#a0380d1619a4fdac78ae5bfa7f2b68832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#aae2e4a2445610ae8ab1d4aba35ad36b7">PrefixKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633bfa32e2919311ac4c7445e29587d0">emitREXPrefix</a> (int MemOperand, const MCInst &amp;MI, const MCSubtargetInfo &amp;STI, SmallVectorImpl&lt; char &gt; &amp;CB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit REX prefix which specifies 1) 64-bit instructions, 2) non-default operand size, and 3) use of X86-64 extended registers. <a href="#a633bfa32e2919311ac4c7445e29587d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfeed4aad2aba9f5e356d204ebf81894">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a56a5c9845f4dee3336c3d5e5c9d4aa">Ctx</a></td>
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


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86MCCodeEmitter() {#a66a91a4b7ba7dadf46425e8bbb463e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::X86MCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; mcii, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a34ed0845f8ed3b20f6b9f70e9d103186">llvm::createX86MCCodeEmitter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#ac6e1cdbd935a8cc82d9f9f3e1cead86b">llvm::X86_MC::emitPrefix</a>, <a href="#a699a1d43432a5ce0bbdaa90f3c3e9d21">operator=</a> and <a href="#a5d03bfbb5ef9339d763877e8eed11e1e">X86MCCodeEmitter</a>.</p>

</div>
</div>

### X86MCCodeEmitter() {#a5d03bfbb5ef9339d763877e8eed11e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::X86MCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter">X86MCCodeEmitter</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="#a66a91a4b7ba7dadf46425e8bbb463e5f">X86MCCodeEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~X86MCCodeEmitter() {#a90a9b636f13b82da7f22637018777935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::~X86MCCodeEmitter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a380773ba72f8745ffdea347917d48a95">emitPrefix</a>, <a href="#a326c8dcef7365124098e7573ebe4bd31">encodeInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a699a1d43432a5ce0bbdaa90f3c3e9d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86MCCodeEmitter &amp; anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter">X86MCCodeEmitter</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="#a66a91a4b7ba7dadf46425e8bbb463e5f">X86MCCodeEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitPrefix() {#a380773ba72f8745ffdea347917d48a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitPrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#af0baab1b1dfea49cbffeb8727aebd429">llvm::X86II::getOperandBias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a8da88ee0688eaec097d62d33fff86992">llvm::X86II::isPseudo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#ac6e1cdbd935a8cc82d9f9f3e1cead86b">llvm::X86_MC::emitPrefix</a> and <a href="#a90a9b636f13b82da7f22637018777935">~X86MCCodeEmitter</a>.</p>

</div>
</div>

### encodeInstruction() {#a326c8dcef7365124098e7573ebe4bd31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::encodeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3db5b7855daab5b642f29a4f8743d1a9">llvm::X86II::AddCCFrm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5cd1bb6ca4bb8d7b507c98b61a19ae77">llvm::X86II::AddRegFrm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">llvm::X86::AddrNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#ab04a741cd062f6096b5181ada9b27489">anonymous{X86MCCodeEmitter.cpp}::emitByte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">llvm::X86II::EVEX_K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0c7b9207abbba8cff7c96ce0b4439690">llvm::X86II::EVEX_RC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">llvm::X86II::FormMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ac5e00b79e046b7edec72a31f9398ea75">llvm::X86II::getBaseOpcodeFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#af0baab1b1dfea49cbffeb8727aebd429">llvm::X86II::getOperandBias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ab80f6be5c11059e150772326c6a5e293">llvm::X86II::getSizeOfImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a3bab7f646d8804292fe0561f29f0c9c0">llvm::X86II::hasNewDataDest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea79b6fe6fc9adb2637eb289c0b1f27613">llvm::X86II::Imm8Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8">llvm::X86II::ImmMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3682f9c28dce92228badc39d606d2664">isPCRel32Branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a8da88ee0688eaec097d62d33fff86992">llvm::X86II::isPseudo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a624d914db11b33bdb836e37b51b9d2f5">modRMByte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac9be8e1d01f704feb05bd77f9454d9c4">llvm::X86II::MRM0m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea594ebf9b65f24cace8a6ed6cc4c188dc">llvm::X86II::MRM0r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0107a9570489e513aeb2c457c1bc4ea7">llvm::X86II::MRM0X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2907aae414f1869eede11975c90ca55e">llvm::X86II::MRM1m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf4593f298ffcbd9b56cccee8c9b08f4f">llvm::X86II::MRM1r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea38b0803128a680769157e24858a8fcec">llvm::X86II::MRM1X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab2b54a959754806bbcc10c7d415869b4">llvm::X86II::MRM2m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea50b127ece65d9d64ecff049972c908a7">llvm::X86II::MRM2r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8ffd3410ef34800d44d089d1204ab80a">llvm::X86II::MRM2X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eae6c25fb53fc239290474f16af2896017">llvm::X86II::MRM3m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eae3f4d0f3323d02cfb646af18c329dcc1">llvm::X86II::MRM3r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8cd6a8196a06c9a17ef03ad258199b56">llvm::X86II::MRM3X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3b73d9e91703e440c64df61ab7cc1997">llvm::X86II::MRM4m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf2b510dd27c823fbcb97dccc422165dc">llvm::X86II::MRM4r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaa594aa3985a0795387aa7af8947b1e36">llvm::X86II::MRM4X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0420bc5bdfc993b20046f32d50fa0753">llvm::X86II::MRM5m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1ccd60dae6f567df2362f05b10053f2c">llvm::X86II::MRM5r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab383ad975c3b9092939504e4cfe2ae1b">llvm::X86II::MRM5X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf1e55f460320e2a89ccd653477a81909">llvm::X86II::MRM6m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eafe4134fe8da389ed6dbaddff7d04e924">llvm::X86II::MRM6r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8b62cf7e7b7cd325706f22acc7a534d6">llvm::X86II::MRM6X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea792ba63c3af3d1eed02519bbc1f883c2">llvm::X86II::MRM7m</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea48bbc6e11eab7158eca421cdbefb4300">llvm::X86II::MRM7r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea7f05c49c45f8901eb86ef2cae982fb87">llvm::X86II::MRM7X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2af966e37189622a1946ce35593a47c1">llvm::X86II::MRM_C0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eadf13526f9c198e6d3c44b18fade1cdaa">llvm::X86II::MRM_C1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea189edb0057c77e393b6cd48c6a57844f">llvm::X86II::MRM_C2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0b8663d52f6013c3c4c44ee6b3e4c221">llvm::X86II::MRM_C3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaec272046d5dd90472121b5a374c10c13">llvm::X86II::MRM_C4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2a6bc67c716424a75afd98493ce44ca7">llvm::X86II::MRM_C5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1511d6f7eff51b12b38d9f86c132b3a5">llvm::X86II::MRM_C6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea20fa7bc944e07c156d78ee9f5ee4c04c">llvm::X86II::MRM_C7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea37445de2099407dfca0ec37ff35fe5d5">llvm::X86II::MRM_C8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0125d0cd4af4273d1367a6c462839199">llvm::X86II::MRM_C9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5b915593c95df3a2d84c96327151320d">llvm::X86II::MRM_CA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea395918f662de770c178e7f7e544934ba">llvm::X86II::MRM_CB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8fbd1ccdaf11ee40122c547614c78a10">llvm::X86II::MRM_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea776deddd1d12c851740c6c5a42da0fd0">llvm::X86II::MRM_CD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea7a707f8b06bf47ba3bfe19ddd4a4de26">llvm::X86II::MRM_CE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea4f3138e38a1ffc21e8e279506282fdc4">llvm::X86II::MRM_CF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaa9cc16d23eb1dbbd266f08d5b72c9d3b">llvm::X86II::MRM_D0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3bcf50adb50e141c86c2207c2665a914">llvm::X86II::MRM_D1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea19e5fd422fa45df8331f702e30a3b23d">llvm::X86II::MRM_D2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eacf475f7fa1990d9771867a43a5cb85b2">llvm::X86II::MRM_D3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaeaa884b20defdb5c6e68fad5b0292c5e">llvm::X86II::MRM_D4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0463837736d6ed75cc0575e546ad9769">llvm::X86II::MRM_D5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea272fc77667a050402a169a058b0a4743">llvm::X86II::MRM_D6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3bd2db5d167f57e231a3cbda8b47328b">llvm::X86II::MRM_D7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea7a240d439831945855485d9f668be73d">llvm::X86II::MRM_D8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5502e099f8608464260941952d44efd6">llvm::X86II::MRM_D9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab93028e02236b5c4c5d824a31d68805d">llvm::X86II::MRM_DA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea9a3b74dbd24dd89ad5cdca90b5fd868f">llvm::X86II::MRM_DB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea16edad2aa61ba14cb331d3741526c0bc">llvm::X86II::MRM_DC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea571898bf7abbdc75ca1da8810cde5e0f">llvm::X86II::MRM_DD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea248e1fc19cfe5ff9230b7ed6dbf9cd72">llvm::X86II::MRM_DE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaccca1bfb3adb4527dfd581b8d68540a6">llvm::X86II::MRM_DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3063db197181757a6cd1e36cede73a30">llvm::X86II::MRM_E0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3ab2637fb82524a013ea7c723f8c8f63">llvm::X86II::MRM_E1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea75edf85ddb193d591093ce26d7767e4f">llvm::X86II::MRM_E2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabd41e93afa5098b8fbdc4283a4715554">llvm::X86II::MRM_E3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaeeac690144cf1f43a36406182ad141ee">llvm::X86II::MRM_E4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2bad450ca1a94ce69ae415089410766c">llvm::X86II::MRM_E5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea252613e02ec044540f82c75f89f36eef">llvm::X86II::MRM_E6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea00d46302e861a9c7fd9fecff66f57d43">llvm::X86II::MRM_E7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5d145c66ae6d756f9e9ad6ca5679fc30">llvm::X86II::MRM_E8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2926981e23657a2d17b45aa1e8deeb32">llvm::X86II::MRM_E9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf0e0ba20c47f32af24167f89de05ea2b">llvm::X86II::MRM_EA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5e1a684c375625f7e37e9fe1e51e8b11">llvm::X86II::MRM_EB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea404988f54ad3626aa9083dffa10af417">llvm::X86II::MRM_EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6d741c96d1bb53548d70ba69e64dd87f">llvm::X86II::MRM_ED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eadfb7936fa0afa17e28a206fcdbc56f0c">llvm::X86II::MRM_EE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eae82cd5ecc861d5194f989105b9b1a703">llvm::X86II::MRM_EF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea936de17cbfd634fac5595a37a533f95f">llvm::X86II::MRM_F0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead6e835cdd73242accfc715f15582d01d">llvm::X86II::MRM_F1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead97baea9720ca2d954726b6740b7809d">llvm::X86II::MRM_F2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1956e66a1c51c45ba25231fcb34a6aaa">llvm::X86II::MRM_F3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabc0b630f1cb9d56814a374cc7c8e70c7">llvm::X86II::MRM_F4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea88119e0502acf1a1ec6650f4435f9924">llvm::X86II::MRM_F5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea421213d9262af8d681a60931da2ea361">llvm::X86II::MRM_F6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea599cbf1248343a8255a40b76010a699f">llvm::X86II::MRM_F7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaaf1c2bcbf66b594cb5ef0710023eaa2a">llvm::X86II::MRM_F8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea44d10b054bc67d9b6f1a07b9dc0d18ee">llvm::X86II::MRM_F9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea2d11d20093f76b091589d4ef0eaceae4">llvm::X86II::MRM_FA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6f05cf3244440c8e67134b48bc940c36">llvm::X86II::MRM_FB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac2a2c7a6e424ee9aa0011460a4d21a06">llvm::X86II::MRM_FC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8f7673a5f185e5d03e0b82c20e00a482">llvm::X86II::MRM_FD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead28e78f91e2f75cc5ad3d84154e7438b">llvm::X86II::MRM_FE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eacb535be85414635d6cbbaa53f67167cd">llvm::X86II::MRM_FF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8de627e0b4d8f49621aaffaf22768ccf">llvm::X86II::MRMDestMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea39ff7e3b87758fceb290c859e5525b92">llvm::X86II::MRMDestMem4VOp3CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaa9e2dd541cca69dae4eb2b19c12a920a">llvm::X86II::MRMDestMemCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5a693dd88d31ce75ba797dca591201dc">llvm::X86II::MRMDestMemFSIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabe42ba2fb12010736a3d91ff51c00f91">llvm::X86II::MRMDestReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea7ea417afb58cc07fa2cfcae87905361c">llvm::X86II::MRMDestRegCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea47511fb3305bca93e2f5a8b5c06cd434">llvm::X86II::MRMr0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabeb3b7e6c5b8fde8b53c453b462f0aae">llvm::X86II::MRMSrcMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea71ff3202ae1a689c037fdde29b3ef3d2">llvm::X86II::MRMSrcMem4VOp3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1ba28eab105e932f7173e256119df199">llvm::X86II::MRMSrcMemCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea912fe30bf2fb6db485900f399a0f6919">llvm::X86II::MRMSrcMemFSIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabfcb56e85f0547829052a6f31803159b">llvm::X86II::MRMSrcMemOp4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab5eb1a156b44a8263348720cefb0f078">llvm::X86II::MRMSrcReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaec9007fc8d5e45ac8c8ca70cbc20527c">llvm::X86II::MRMSrcReg4VOp3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac7457861e859e2d45b248505b1ce4d64">llvm::X86II::MRMSrcRegCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaa5752d9fbf4eaf48924623fb22345d78">llvm::X86II::MRMSrcRegOp4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea580f946ce0c61ee2cb39a53181487908">llvm::X86II::MRMXm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaae046536d1fe7157266801c5446581f1">llvm::X86II::MRMXmCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6d334921612f3043e206d194dc882494">llvm::X86II::MRMXr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaa674367c0dc04c60557b71d6cb873cc0">llvm::X86II::MRMXrCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d">llvm::X86II::OpMapMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3f6747b02d6858c6b951b760c4117325">llvm::X86II::PrefixByte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac147ba1bbcbb4cbda038e4fbd6e5bb31">llvm::X86II::Pseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0418cac03c72116432f2161ba81a9477">llvm::X86II::RawFrm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea336cd3807e9712aee813c92ab1cbd3c7">llvm::X86II::RawFrmDst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea0ebbf8b9bdbf40355e1786a06fe3ebdb">llvm::X86II::RawFrmDstSrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab246efb880b0f5ea54ddf3879bced8e3">llvm::X86II::RawFrmImm16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea682f4bde7ea50ebb5d09cfc9f8283d87">llvm::X86II::RawFrmImm8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf45ee1f86f45fd23ef8e084b0069aa17">llvm::X86II::RawFrmMemOffs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab93edaca89956bd35deb0830c0a83c32">llvm::X86II::RawFrmSrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca3b2a5a68543379e2c0ecada70a114244">llvm::X86::reloc_branch_4byte_pcrel</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eace49aa87c8e2d2f284a9a4ce549a97c3">llvm::X86II::ThreeDNow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eae372c99c6166a9dd4cabd6e9e25e8b02">llvm::X86II::TwoConditionalOps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8a71098306ad6ceef2c5cde6440f81ff">llvm::X86II::VEX_4V</a>.</p>


<p>Referenced by <a href="#a90a9b636f13b82da7f22637018777935">~X86MCCodeEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitImmediate() {#ac2f5eebb5cb136ccfeb2e1a4cad662df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned ImmSize, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> FixupKind, uint64_t StartByte, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, int ImmOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitMemModRMByte() {#aa8d824fdec9e34e27bb3710ede2400e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitMemModRMByte (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned Op, unsigned RegOpcodeField, uint64_t TSFlags, <a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#aae2e4a2445610ae8ab1d4aba35ad36b7">PrefixKind</a> Kind, uint64_t StartByte, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, bool ForceSIB=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitOpcodePrefix() {#a0380d1619a4fdac78ae5bfa7f2b68832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrefixKind X86MCCodeEmitter::emitOpcodePrefix (int MemOperand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all instruction prefixes prior to the opcode.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MemOperand</td>
<td class="doxyParamItemDescription"><p>the operand # of the start of a memory operand if present. If not present, it is -1.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the used prefix (REX or None).</p></dd>
</dl>


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitPrefixImpl() {#a927873c0d6057171e1ca4d83ceb000cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrefixKind X86MCCodeEmitter::emitPrefixImpl (unsigned &amp; CurOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all instruction prefixes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>one of the REX, XOP, VEX2, VEX3, EVEX if any of them is used, otherwise returns None.</p></dd>
</dl>


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitRegModRMByte() {#a52ed27aef5b41f919a88ccfcc3291af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitRegModRMByte (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; ModRMReg, unsigned RegOpcodeFld, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitREXPrefix() {#a633bfa32e2919311ac4c7445e29587d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrefixKind X86MCCodeEmitter::emitREXPrefix (int MemOperand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit REX prefix which specifies 1) 64-bit instructions, 2) non-default operand size, and 3) use of X86-64 extended registers.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the used prefix (REX or None).</p></dd>
</dl>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitSegmentOverridePrefix() {#a5ab5979a635c31462c9e9f398d862d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitSegmentOverridePrefix (unsigned SegOperand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit segment override opcode prefix as needed.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitSIBByte() {#ae9d7243a5b6afc8efbd07e7eb0f52eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCCodeEmitter::emitSIBByte (unsigned SS, unsigned Index, unsigned Base, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### emitVEXOpcodePrefix() {#a72c6075fcce68f7258885e1228ce5332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrefixKind X86MCCodeEmitter::emitVEXOpcodePrefix (int MemOperand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit XOP, VEX2, VEX3 or EVEX prefix.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the used prefix.</p></dd>
</dl>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### getX86RegEncoding() {#a64bdd5cc5c04afe9c994f2f2c234ac68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86MCCodeEmitter::getX86RegEncoding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### getX86RegNum() {#ae0c2bf2c1fc729d5f86009f36533a6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86MCCodeEmitter::getX86RegNum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a7a56a5c9845f4dee3336c3d5e5c9d4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

### MCII {#abfeed4aad2aba9f5e356d204ebf81894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo&amp; anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp">X86MCCodeEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
