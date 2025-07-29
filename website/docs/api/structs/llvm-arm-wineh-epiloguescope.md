---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/arm/wineh/epiloguescope
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `EpilogueScope` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord">ExceptionDataRecord</a> - An entry in the table of exception data (.xdata) <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ARM::WinEH::EpilogueScope { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">llvm/Support/ARMWinEH.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36c0f761bc889edd17953a79056e4e2">EpilogueScope</a> (const support::ulittle32_t Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f719f3030062c18119f52ef29d596a2">EpilogueStartOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091fdd44d698bdded70898d916977c45">ResARM</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a5ffda8feda4ff92198f5793db4c46">ResAArch64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fedca71fc57023b360b39ecda2c069a">Condition</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76a34504b65a7005760348a2e699742">EpilogueStartIndexARM</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55f0ef46220287826415a6b94cb6847">EpilogueStartIndexAArch64</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465355f44b5483ff629b1a0712a817ed">ES</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/arm/wineh/exceptiondatarecord">ExceptionDataRecord</a> - An entry in the table of exception data (.xdata)</p>


<p>The format on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> is:</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +----—+------—+-+-+-+—+--------------------------------—+ | C Wrd | Epi Cnt |F|E|X|Ver| <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length | +----—+-----—+'-'-'-'—'—+----------------------------—+ | Reserved |Ex. Code Words| (Extended Epilogue Count) | +----—+-----—+-----------—+----------------------------—+</p>


<p>The format on ARM64 is:</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +------—+------—+-+-+—+--------------------------------—+ | C Wrd | Epi Cnt |E|X|Ver| <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length | +------—+---—+–'-'-'—'—+----------------------------—+ | Reserved |Ex. Code Words| (Extended Epilogue Count) | +----—+-----—+-----------—+----------------------------—+</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length : 18-bit field indicating the total length of the function in bytes divided by 2. If a function is larger than 512KB, then multiple pdata and xdata records must be used. Vers : 2-bit field describing the version of the remaining structure. Only version 0 is currently defined (values 1-3 are not permitted). X : 1-bit field indicating the presence of exception data E : 1-bit field indicating that the single epilogue is packed into the header F : 1-bit field indicating that the record describes a function fragment (implies that no prologue is present, and prologue processing should be skipped) (<a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> only) Epilogue Count : 5-bit field that differs in meaning based on the E field.</p>



<pre><code>             If E is set, then this field specifies the index of the
             first unwind code describing the (only) epilogue.

             Otherwise, this field indicates the number of exception
             scopes.  If more than 31 scopes exist, then this field and
             the Code Words field must both be set to 0 to indicate that
             an extension word is required.
</code></pre>


<p>Code Words : 4-bit (5-bit on ARM64) field that specifies the number of 32-bit words needed to contain all the unwind codes. If more than 15 words (31 words on ARM64) are required, then this field and the Epilogue Count field must both be set to 0 to indicate that an extension word is required. Extended Epilogue Count, Extended Code Words : Valid only if Epilog Count and Code Words are both set to 0. Provides an 8-bit extended code word count and 16-bits for epilogue count</p>


<p>The epilogue scope format on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> is:</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +-------------—+---—+—+—+----------------------------—+ | Ep Start Idx | Cond |Res| Epilogue Start Offset | +-------------—+---—+—+--------------------------------—+</p>


<p>The epilogue scope format on ARM64 is:</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +----------------—+----—+—+----------------------------—+ | Ep Start Idx | Res | Epilogue Start Offset | +----------------—+----—+--------------------------------—+</p>


<p>If the E bit is unset in the header, the header is followed by a series of epilogue scopes, which are sorted by their offset.</p>


<p>Epilogue Start Offset: 18-bit field encoding the offset of epilogue relative to the start of the function in bytes divided by two Res : 2-bit field reserved for future expansion (must be set to 0) Condition : (<a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> only) 4-bit field providing the condition under which the epilogue is executed. Unconditional epilogues should set this field to 0xe. Epilogues must be entirely conditional or unconditional, and in Thumb-2 mode. The epilogue begins with the first instruction after the IT opcode. Epilogue Start Index : 8-bit field indicating the byte index of the first unwind code describing the epilogue</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +------------—+------------—+------------—+------------—+ | Unwind Code 3 | Unwind Code 2 | Unwind Code 1 | Unwind Code 0 | +------------—+------------—+------------—+------------—+</p>


<p>Following the epilogue scopes, the byte code describing the unwinding follows. This is padded to align up to word alignment. Bytes are stored in little endian.</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +------------------------------------------------------------—+ | Exception Handler RVA (requires X = 1) | +------------------------------------------------------------—+ | (possibly followed by data required for exception handler) | +------------------------------------------------------------—+</p>


<p>If the X bit is set in the header, the unwind byte code is followed by the exception handler information. This constants of one Exception Handler RVA which is the address to the exception handler, followed immediately by the variable length data associated with the exception handler.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EpilogueScope() {#ae36c0f761bc889edd17953a79056e4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::EpilogueScope::EpilogueScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> Data)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Condition() {#a1fedca71fc57023b360b39ecda2c069a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::EpilogueScope::Condition ()</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

### EpilogueStartIndexAArch64() {#ae55f0ef46220287826415a6b94cb6847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::ARM::WinEH::EpilogueScope::EpilogueStartIndexAArch64 ()</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

### EpilogueStartIndexARM() {#aa76a34504b65a7005760348a2e699742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::EpilogueScope::EpilogueStartIndexARM ()</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

### EpilogueStartOffset() {#a6f719f3030062c18119f52ef29d596a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::EpilogueScope::EpilogueStartOffset ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

### ResAArch64() {#a52a5ffda8feda4ff92198f5793db4c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::EpilogueScope::ResAArch64 ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

### ResARM() {#a091fdd44d698bdded70898d916977c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::EpilogueScope::ResARM ()</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a465355f44b5483ff629b1a0712a817ed">ES</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ES {#a465355f44b5483ff629b1a0712a817ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t llvm::ARM::WinEH::EpilogueScope::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#a1fedca71fc57023b360b39ecda2c069a">Condition</a>, <a href="#ae36c0f761bc889edd17953a79056e4e2">EpilogueScope</a>, <a href="#ae55f0ef46220287826415a6b94cb6847">EpilogueStartIndexAArch64</a>, <a href="#aa76a34504b65a7005760348a2e699742">EpilogueStartIndexARM</a>, <a href="#a6f719f3030062c18119f52ef29d596a2">EpilogueStartOffset</a>, <a href="#a52a5ffda8feda4ff92198f5793db4c46">ResAArch64</a> and <a href="#a091fdd44d698bdded70898d916977c45">ResARM</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
