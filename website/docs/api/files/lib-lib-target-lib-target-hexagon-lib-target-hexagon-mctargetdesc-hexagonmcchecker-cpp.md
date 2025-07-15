---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonMCChecker.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-h">MCTargetDesc/HexagonMCChecker.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonbaseinfo-h">MCTargetDesc/HexagonBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">MCTargetDesc/HexagonMCShuffler.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">MCTargetDesc/HexagonMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include &lt;cassert&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ea14078b9e61b0e51611705515cc6c">isDuplexAGroup</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec42fbce291c77743d74805b379a0558">isNeitherAnorX</a> (MCInstrInfo const &amp;MCII, MCInst const &amp;ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f1f1a4fa2298e41c9b224c74793f7c">RelaxNVChecks</a>("relax-nv-checks", cl::Hidden, cl::desc("Relax checks of new-value validity"))</td>
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

### isDuplexAGroup() {#ab1ea14078b9e61b0e51611705515cc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDuplexAGroup (unsigned Opcode)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp">HexagonMCChecker.cpp</a>.</p>


<p>Referenced by <a href="#aec42fbce291c77743d74805b379a0558">isNeitherAnorX</a>.</p>

</div>
</div>

### isNeitherAnorX() {#aec42fbce291c77743d74805b379a0558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNeitherAnorX (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; ID)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp">HexagonMCChecker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="#ab1ea14078b9e61b0e51611705515cc6c">isDuplexAGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af9c1fb4944fcf1d6aadc0f51a69b56e9">llvm::HexagonMCInstrInfo::isFloat</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807af587caa3f5623f75f5c70393039bd1d2">llvm::HexagonII::TypeALU32_2op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a252bb34d9b721a8e353e6dc4deefe5da">llvm::HexagonII::TypeALU32_3op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a339127cb32340583942dee2cd6883db6">llvm::HexagonII::TypeALU32_ADDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a164b5513f04d48deaa408d128e26331e">llvm::HexagonII::TypeALU64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a27b04989c8ab303f66b288add9bae068">llvm::HexagonII::TypeDUPLEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a60b35308a0a70166e236a990524eb366">llvm::HexagonII::TypeEXTENDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a99b35d8c2faa352d834f3ae47577f687">llvm::HexagonII::TypeM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac8da00149d1745b31ed82eae6e24309f">llvm::HexagonII::TypeS_2op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807adcd6a5ee0158bda659f9cdd5122efeb2">llvm::HexagonII::TypeS_3op</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ae794ca518412fb02775c746d4d8db63c">llvm::HexagonII::TypeSUBINSN</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### RelaxNVChecks {#a18f1f1a4fa2298e41c9b224c74793f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RelaxNVChecks("relax-nv-checks", cl::Hidden, cl::desc("Relax checks of new-value validity"))</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcchecker-cpp">HexagonMCChecker.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
