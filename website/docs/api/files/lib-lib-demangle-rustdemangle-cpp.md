---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/demangle/rustdemangle-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RustDemangle.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangle-h">llvm/Demangle/Demangle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h">llvm/Demangle/StringViewExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/utility-h">llvm/Demangle/Utility.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include &lt;limits&gt;
#include &lt;string_view&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-">anonymous{RustDemangle.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-rustdemangle-cpp-/identifier">Identifier</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rustdemangle-cpp-/demangler">Demangler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d4f37888b638bcbd9fc0201492c776">isDigit</a> (const char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05944bb87057627a566963c526f1ca5">isHexDigit</a> (const char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dadba0c2f6f1598969e8a239f7f6dd">isLower</a> (const char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4409626828d300c2f2c6db00ca48303">isUpper</a> (const char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103d8cfe62c1651cd70e181746f8a840">isValid</a> (const char C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if C is a valid mangled character: &lt;0-9a-zA-Z_&gt;. <a href="#a103d8cfe62c1651cd70e181746f8a840">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e6ec39071966ab20623c3bd1718e9b">parseBasicType</a> (char C, BasicType &amp;Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f8929de72b35003da71267190a3e40">isAsciiPrintable</a> (uint64_t CodePoint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if CodePoint represents a printable ASCII character. <a href="#a33f8929de72b35003da71267190a3e40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbfab3fd45a1a0cc17bf9f8f0b3bd3d">decodePunycodeDigit</a> (char C, size_t &amp;Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880d5f28abcbc9f6f2d6632bd8f93c4d">removeNullBytes</a> (OutputBuffer &amp;Output, size_t StartIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c06f8719364f2573032eefdd41d8ba">encodeUTF8</a> (size_t CodePoint, char *Output)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a> (std::string_view Input, OutputBuffer &amp;Output)</td>
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

### decodePunycode() {#ad70908652bd5b04580fa8bd87c85f701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool decodePunycode (std::string_view Input, <a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; Output)</td>
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



<p>Definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a1fbfab3fd45a1a0cc17bf9f8f0b3bd3d">decodePunycodeDigit</a>, <a href="#a93c06f8719364f2573032eefdd41d8ba">encodeUTF8</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#adae4954f6d152eb88c24622d8810c813">OutputBuffer::getCurrentPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#ae8f0bd74643fb4035d3992af214b44a3">OutputBuffer::insert</a>, <a href="#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a880d5f28abcbc9f6f2d6632bd8f93c4d">removeNullBytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### decodePunycodeDigit() {#a1fbfab3fd45a1a0cc17bf9f8f0b3bd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool decodePunycodeDigit (char C, size_t &amp; Value)</td>
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



<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a12d4f37888b638bcbd9fc0201492c776">isDigit</a> and <a href="#aa1dadba0c2f6f1598969e8a239f7f6dd">isLower</a>.</p>


<p>Referenced by <a href="#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a>.</p>

</div>
</div>

### encodeUTF8() {#a93c06f8719364f2573032eefdd41d8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool encodeUTF8 (size_t CodePoint, char * Output)</td>
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



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>Referenced by <a href="#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aefed9cb3f107aee0cff4d325c7d689ae">llvm::yaml::escape</a>.</p>

</div>
</div>

### isAsciiPrintable() {#a33f8929de72b35003da71267190a3e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAsciiPrintable (uint64_t CodePoint)</td>
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

<p>Returns true if CodePoint represents a printable ASCII character.</p>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>

</div>
</div>

### isDigit() {#a12d4f37888b638bcbd9fc0201492c776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDigit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char C)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a3989cbad7cca2a86cb7d3a0627748b">llvm::StringRef::compare_numeric</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa49cf0e393f7067f09985cec1d4b7387">convertStrToInt</a>, <a href="#a1fbfab3fd45a1a0cc17bf9f8f0b3bd3d">decodePunycodeDigit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#ae263aed138fcb0a6ceea9c9f29fcfb8d">llvm::symbolize::anonymous{Symbolize.cpp}::demanglePE32ExternCFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp/#acd47c935110e24d04ed336c214ee8a6d">doHexLookAhead</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#ab3836b4bb1237941003273adb235b8e2">anonymous{AMDGPULibFunc.cpp}::eatNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a3dba4372ba2b0183b65fcce9e61ca7bc">findLastNonVersionCharacter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp/#a4183ffbb055bd5689d234921349a02a8">GetAutoSenseRadix</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-cpp/#a83884a0d8fa84acdbd02874c7994b881">isValidIDChar</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a>, <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/recordparts/#ab6f58b67225aaf63ec2aeee94dd053f4">llvm::LessRecordRegister::RecordParts::RecordParts</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isHexDigit() {#aa05944bb87057627a566963c526f1ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isHexDigit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char C)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmlexer-cpp/#acd47c935110e24d04ed336c214ee8a6d">doHexLookAhead</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-9d99cee30155623a4c4295fc3384ef15/#a845b3d5882fd989ac76b445ada27c7ed">llvm::yaml::ScalarTraits&lt; FixedSizeHex&lt; N &gt; &gt;::input</a> and <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#ad1eaa25f920b0fd6f7ad1e7c6bf8d0c8">llvm::AsmLexer::LexToken</a>.</p>

</div>
</div>

### isLower() {#aa1dadba0c2f6f1598969e8a239f7f6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLower (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char C)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a1fbfab3fd45a1a0cc17bf9f8f0b3bd3d">decodePunycodeDigit</a>, <a href="#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp/#ae0834ffd88d8197c3afbc8c356cfb27a">singleLetterExtensionRank</a>.</p>

</div>
</div>

### isUpper() {#af4409626828d300c2f2c6db00ca48303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUpper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char C)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a103d8cfe62c1651cd70e181746f8a840">isValid</a>.</p>

</div>
</div>

### isValid() {#a103d8cfe62c1651cd70e181746f8a840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValid (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char C)</td>
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

<p>Returns true if C is a valid mangled character: &lt;0-9a-zA-Z_&gt;.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="#aa1dadba0c2f6f1598969e8a239f7f6dd">isLower</a> and <a href="#af4409626828d300c2f2c6db00ca48303">isUpper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvduplicatestrackerbase/#a1c61507b6c7168368caa6bf4ac68f3a9">llvm::SPIRVDuplicatesTrackerBase&lt; KeyTy &gt;::add</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2ce07f2980494b70fbc5b5c8b7eac63a">llvm::dwarf_linker::parallel::CompileUnit::assignTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6ab34a535b1441b48a0ede2c2aa6fb98">llvm::MachineIRBuilder::buildConstDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a92bad84c9e323ab0a96d8d8bbb22d149">llvm::MachineIRBuilder::buildDirectDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab107810eccfb0e46e47348ea9ef8d0ed">llvm::MachineIRBuilder::buildFIDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a5a76abb6dd3946ca5c9cd6e8f341d63c">llvm::MachineIRBuilder::buildIndirectDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2daca542c8dc98439d2a5a86196e0fc8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#af9d05205b22b79b40070ddc105679c7c">collectVirtRegShapes</a>, <a href="#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#a65894464e2ca592db70001e29ac4f1b0">llvm::DiagnosticInfoRegAllocFailure::DiagnosticInfoRegAllocFailure</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a3af1ce05932756a9695dbe24512cb40e">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::encodeVTYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset/#a16a780296035cd55839932310e5dc672">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::findIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#ad78b447d6a130e6102f95a35c58bef9e">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::getSEWLMULRatio</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a3428818c38247f58e3b497e10d49df12">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameVLMAX</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#ab2b86fba641fa9cf7caaf314b2dc9b49">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasSameVTYPE</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#ac8b853a0e5f59f4df074f6ca1f6215cd">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::intersect</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#a6a9fd1a6a02a1df3f9ca79d94c0418a8">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::intersect</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#a0d3afe26f8a5fd873ad5c641b8cf38ce">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::intersectAnticipated</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#af2c46f20e8b768f86d9bbc78c610defc">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::isCompatible</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#a63672bd06cae85a3209b2752fd27b5ed">anonymous{LoopStrengthReduce.cpp}::Cost::isLoser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcregisterinfo-cpp-/mcregaliasiteratorimpl/#af52a9ac61bb053af83542e8eee6b3446">anonymous{MCRegisterInfo.cpp}::MCRegAliasIteratorImpl::operator++</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a93bf89ac71202629a6786d6491092131">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#ac8e19535b49f86145d09b7987bd5bf79">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aab493b5628399b1140af4094f7af919e">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#ac9eba4861a2e3d533aed860e978898e9">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a7715801da0e918c5f258f40246742a1a">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#aa4ed778e7cf004e26e2bd53b5b5de8a1">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::setVTYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### parseBasicType() {#ae9e6ec39071966ab20623c3bd1718e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseBasicType (char C, BasicType &amp; Type)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7ac26f15e86e3de4c398a8273272aba034">anonymous{RustDemangle.cpp}::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a8e95e84813830072b7516cfaa7dbc1a9">anonymous{RustDemangle.cpp}::Char</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a44ad4ef5a76e6aa6fb3e3fa079a54fda">anonymous{RustDemangle.cpp}::F32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a1ad5f6f3069070ec4cbbdc94d5e61e0e">anonymous{RustDemangle.cpp}::F64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7abdebdd2111fb592af2aee43d634d1770">anonymous{RustDemangle.cpp}::I128</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7abcd774f891b5f9df7099f3ea75dadf8d">anonymous{RustDemangle.cpp}::I16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7ad878ea6016bfe01729548bf442de5a8b">anonymous{RustDemangle.cpp}::I32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7ae7e62f6928f76df671b5a0379793fab6">anonymous{RustDemangle.cpp}::I64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a5aef4e3ea379fa0eb2bf42d979443902">anonymous{RustDemangle.cpp}::I8</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a4c29c83e6eefd2c3138aa0b381d0ffa2">anonymous{RustDemangle.cpp}::ISize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a6e7b34fa59e1bd229b207892956dc41c">anonymous{RustDemangle.cpp}::Never</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a68753d36ec0c4d7768b20993268d68d1">anonymous{RustDemangle.cpp}::Placeholder</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7aebccbbd337efb2ddb5979c57125bad1b">anonymous{RustDemangle.cpp}::Str</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a7dd7b3f71c4453011f83e8983df0a1aa">anonymous{RustDemangle.cpp}::U128</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7aef9ef3ebca4d2b64b6ec83808bafa5f2">anonymous{RustDemangle.cpp}::U16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7ac8bd5bedff8ef192d39a962afc0e19ee">anonymous{RustDemangle.cpp}::U32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a31d65cccd6593e4101db93fb878abcaa">anonymous{RustDemangle.cpp}::U64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a6669348b484e3008dca2bfa8e85e40b5">anonymous{RustDemangle.cpp}::U8</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7a19c562a36aeb455d09534f93b4f5236f">anonymous{RustDemangle.cpp}::Unit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7ae73f8909649e05430535582624833e16">anonymous{RustDemangle.cpp}::USize</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-rustdemangle-cpp-/#a76a6de3bfe4b34e80479b5139aae1ab7af685215eb39877e52230b1ab92a4cf3b">anonymous{RustDemangle.cpp}::Variadic</a>.</p>

</div>
</div>

### removeNullBytes() {#a880d5f28abcbc9f6f2d6632bd8f93c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeNullBytes (<a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> &amp; Output, size_t StartIdx)</td>
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



<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp">RustDemangle.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/outputbuffer/#a8ab399f586318b61b6a38a18adbb098f">OutputBuffer::getBuffer</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#adae4954f6d152eb88c24622d8810c813">OutputBuffer::getCurrentPosition</a> and <a href="/web-llvm/docs/api/classes/outputbuffer/#acd4c9686ed303f299f1b5980efce07da">OutputBuffer::setCurrentPosition</a>.</p>


<p>Referenced by <a href="#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
