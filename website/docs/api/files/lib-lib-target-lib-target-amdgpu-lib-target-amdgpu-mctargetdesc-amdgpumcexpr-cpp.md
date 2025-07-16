---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPUMCExpr.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-h">AMDGPUMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcassembler-h">llvm/MC/MCAssembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;optional&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f39ae70bb42dcefd66f58640f9752a8">op</a> (AMDGPUMCExpr::VariantKind Kind, int64_t Arg1, int64_t Arg2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af1c2f9cad56166d08fabb205463d15">fromOptionalToKnownBits</a> (std::optional&lt; bool &gt; CompareResult)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a> (const MCExpr *Expr, KnownBitsMap &amp;KBM, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a> (const MCExpr *Expr, KnownBitsMap &amp;KBM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256114e633f673cf57611169e1ade5c6">unaryOpKnownBitsMapHelper</a> (const MCExpr *Expr, KnownBitsMap &amp;KBM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> (const MCExpr *Expr, KnownBitsMap &amp;KBM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> (const MCExpr *Expr, KnownBitsMap &amp;KBM, MCContext &amp;Ctx)</td>
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

## Typedefs

### KnownBitsMap {#ad24362d061320ed931e732d1fd3a1f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using KnownBitsMap =  DenseMap&lt;const MCExpr *, KnownBits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### binaryOpKnownBitsMapHelper() {#a4d74a9468cededc1f4e9887dd009fe66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void binaryOpKnownBitsMapHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> &amp; KBM, unsigned Depth)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">llvm::KnownBits::add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">llvm::MCBinaryExpr::Div</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">llvm::MCBinaryExpr::EQ</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0aef6b7958c3eebec986bd226aca7325">llvm::KnownBits::eq</a>, <a href="#a2af1c2f9cad56166d08fabb205463d15">fromOptionalToKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">llvm::MCBinaryExpr::GT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">llvm::MCBinaryExpr::GTE</a>, <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">llvm::MCBinaryExpr::LAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">llvm::MCBinaryExpr::LOr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">llvm::MCBinaryExpr::LT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">llvm::MCBinaryExpr::LTE</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">llvm::MCBinaryExpr::Mod</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">llvm::MCBinaryExpr::NE</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2d526cdaed505fb03e49f7bd0c96724f">llvm::KnownBits::ne</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a466e550382eee7535225b95ef91914d1">llvm::KnownBits::sge</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ad20d9f61ec3c5c2a0bd9163cb6c15335">llvm::KnownBits::sgt</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#acc61013b6ddecc5b9c8105aa961b71f2">llvm::KnownBits::sle</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a97cc47234699c26a59495f019e3fb1e3">llvm::KnownBits::slt</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a905d2324c26b7a6f5aeb929a734ce0bc">llvm::KnownBits::srem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aaedcbc66cfec0117e98d503c89234716">llvm::KnownBits::sub</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">llvm::MCBinaryExpr::Xor</a>.</p>


<p>Referenced by <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>.</p>

</div>
</div>

### fromOptionalToKnownBits() {#a2af1c2f9cad56166d08fabb205463d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits fromOptionalToKnownBits (std::optional&lt; bool &gt; CompareResult)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a>.</p>


<p>Referenced by <a href="#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### knownBitsMapHelper() {#aa61330239617d3120b453b49c8654d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void knownBitsMapHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> &amp; KBM, unsigned Depth=0)</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">llvm::MCExpr::Binary</a>, <a href="#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">llvm::MCExpr::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">llvm::MCExpr::Unary</a> and <a href="#a256114e633f673cf57611169e1ade5c6">unaryOpKnownBitsMapHelper</a>.</p>


<p>Referenced by <a href="#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aafd3b7d8deff060578db9e6e6529ef0a">llvm::AMDGPU::foldAMDGPUMCExpr</a>, <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> and <a href="#a256114e633f673cf57611169e1ade5c6">unaryOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### op() {#a7f39ae70bb42dcefd66f58640f9752a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t op (<a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64e">AMDGPUMCExpr::VariantKind</a> Kind, int64_t Arg1, int64_t Arg2)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0">llvm::AMDGPUMCExpr::AGVK_Max</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc">llvm::AMDGPUMCExpr::AGVK_Or</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### targetOpKnownBitsMapHelper() {#a0243f30368fd176bd411351538a11c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void targetOpKnownBitsMapHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> &amp; KBM, unsigned Depth)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea4f4d41a1b5065704c6265c1d247e1f9e">llvm::AMDGPUMCExpr::AGVK_AlignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea8014f0c199aed5816661d1d3f14ac1fc">llvm::AMDGPUMCExpr::AGVK_ExtraSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64eade9b37ace7482eb448727fdbd65a75f0">llvm::AMDGPUMCExpr::AGVK_Max</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea1390ea547d87d17899b5bf826b26ac96">llvm::AMDGPUMCExpr::AGVK_Occupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea5f70392190112d47213e6cc3df8bf8cc">llvm::AMDGPUMCExpr::AGVK_Or</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac4e921b9d06cd1d20aa4994fc39ec64ea7d773e01afab66dff838bb1d5130fd5b">llvm::AMDGPUMCExpr::AGVK_TotalNumVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a3118fd234d0cd907ed2e253fb2d41c0d">llvm::MCExpr::evaluateAsAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a01629bf98f076a28c7b9b6f749cf1362">llvm::AMDGPUMCExpr::getArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#af13ba175af48ccb8caee3131ff1f4b7d">llvm::AMDGPUMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac03d9d83552b7841365415497274cb72">llvm::AMDGPUMCExpr::getSubExpr</a>, <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5120eaa394627e6c1ec3d66ef77947cd">llvm::KnownBits::umax</a>.</p>


<p>Referenced by <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>.</p>

</div>
</div>

### tryFoldHelper() {#a8ea312e62fba190b14afa1c6cbe79453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * tryFoldHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> &amp; KBM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">llvm::MCBinaryExpr::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">llvm::MCBinaryExpr::And</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">llvm::MCBinaryExpr::AShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">llvm::MCExpr::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">llvm::MCExpr::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a8b210af308c92a311c2a71c9a2ad051a">llvm::AMDGPUMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac393df34745cae1433909c2049978bd4">llvm::MCBinaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a40326528db66cf90324ba646912d634d">llvm::MCUnaryExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a01629bf98f076a28c7b9b6f749cf1362">llvm::AMDGPUMCExpr::getArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#afd1c330d00d17bd267450ab43d5f0eec">llvm::KnownBits::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#af13ba175af48ccb8caee3131ff1f4b7d">llvm::AMDGPUMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#afc4237f50d652cdefff412b2c780c369">llvm::MCExpr::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a5606d070331bbd494bcd8fe374540d4e">llvm::MCBinaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a1032772abdf9ca7296d4b4f35fe199ac">llvm::MCUnaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a7744bb0ad33a4245610b0bb3d7f330ed">llvm::MCUnaryExpr::getSubExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a6dee2d9e1e2a288de903228075ac71de">isConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5274c29c7da2473d342adfa98f34a025">llvm::KnownBits::isConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">llvm::MCBinaryExpr::LShr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">llvm::MCBinaryExpr::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">llvm::MCBinaryExpr::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">llvm::MCBinaryExpr::Shl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">llvm::MCBinaryExpr::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa5928e5c98f309a381e165e774c09f49e">llvm::MCExpr::Unary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aafd3b7d8deff060578db9e6e6529ef0a">llvm::AMDGPU::foldAMDGPUMCExpr</a> and <a href="#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### unaryOpKnownBitsMapHelper() {#a256114e633f673cf57611169e1ade5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void unaryOpKnownBitsMapHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="#ad24362d061320ed931e732d1fd3a1f25">KnownBitsMap</a> &amp; KBM, unsigned Depth)</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp">AMDGPUMCExpr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a1032772abdf9ca7296d4b4f35fe199ac">llvm::MCUnaryExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a7744bb0ad33a4245610b0bb3d7f330ed">llvm::MCUnaryExpr::getSubExpr</a>, <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a36d9168813b2a8415c085ac551c54458">llvm::KnownBits::makeNegative</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a192e15f89a5aa04df018639812e2c4db">llvm::KnownBits::makeNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa23670b83f3704a21f5f8fcaf2701211a">llvm::MCUnaryExpr::Minus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa473ccb44d0bb542a3fa877acde7813ae">llvm::MCUnaryExpr::Not</a> and <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#a6d700a6b938d48f3b3b2d8686adb858fa43f553663c81a0962438aae8d8c44526">llvm::MCUnaryExpr::Plus</a>.</p>


<p>Referenced by <a href="#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
