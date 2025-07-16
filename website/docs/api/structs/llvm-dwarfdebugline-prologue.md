---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfdebugline/prologue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Prologue` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFDebugLine::Prologue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">llvm/DebugInfo/DWARF/DWARFDebugLine.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed4cdb8724ffa55b875906ac41dc7a3">Prologue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c175233d7f52bbd81d731366a8c5ed0">getFormParams</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a106e861c36966e4d25dbb732fc0a7a">getAddressSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435e877cb6f111a61782d078d4abf796">isDWARF64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38113edbada659af2f487d2ceb50c978">sizeofTotalLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf0dc75e536f907bdbec18a48c8adce">sizeofPrologueLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929996e51bac45d53456dacc7b1c4a05">totalLengthIsValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">getLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Length of the prologue in bytes. <a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry">llvm::DWARFDebugLine::FileNameEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2e8b7998b275bb9b237db898f67c42">getFileNameEntry</a> (uint64_t Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get DWARF-version aware access to the file name entry at the provided index. <a href="#a9f2e8b7998b275bb9b237db898f67c42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2815552ca549e1a61b7b87644fafee11">hasFileAtIndex</a> (uint64_t FileIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b80abc56d98c9368d45aff678818371">getLastValidFileIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa47cad32e9eb34704f1ce2ead863e518">getFileNameByIndex</a> (uint64_t FileIndex, StringRef CompDir, DILineInfoSpecifier::FileLineInfoKind Kind, std::string &amp;Result, sys::path::Style Style=sys::path::Style::native) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOptions) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a> (DWARFDataExtractor Data, uint64_t *OffsetPtr, function_ref&lt; void(Error)&gt; RecoverableErrorHandler, const DWARFContext &amp;Ctx, const DWARFUnit *U=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93c8f0490ca204fc5d763a92fa8eb59">TotalLength</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of the statement information for this compilation unit (not including the total_length field itself). <a href="#ac93c8f0490ca204fc5d763a92fa8eb59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Version, address size (starting in v5), and DWARF32/64 format; these parameters affect interpretation of forms (used in the directory and file tables starting with v5). <a href="#ad1a98ac8bd44a05c862c20b5963957d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f8c3dda3a345a78074012970805463">PrologueLength</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes following the prologue_length field to the beginning of the first byte of the statement program itself. <a href="#a31f8c3dda3a345a78074012970805463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cb66612cc59003c75c67e4d6ae4ab3">SegSelectorSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In v5, size in bytes of a segment selector. <a href="#a47cb66612cc59003c75c67e4d6ae4ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea7f31bac618b220bfb554614e042a1">MinInstLength</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size in bytes of the smallest target machine instruction. <a href="#a1ea7f31bac618b220bfb554614e042a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b76c4e63b464e956eec298b0a8057ef">MaxOpsPerInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of individual operations that may be encoded in an instruction. <a href="#a0b76c4e63b464e956eec298b0a8057ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8792778480598c24baa65f25722e4f4">DefaultIsStmt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The initial value of theis_stmtregister. <a href="#ab8792778480598c24baa65f25722e4f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a16cb2aaa44e7c4898bdc0bba3faa7b">LineBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This parameter affects the meaning of the special opcodes. See below. <a href="#a5a16cb2aaa44e7c4898bdc0bba3faa7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b88316d7e742255b1073a0911009105">LineRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This parameter affects the meaning of the special opcodes. See below. <a href="#a6b88316d7e742255b1073a0911009105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821d6d9a98cbab9707c78bf0db7c0989">OpcodeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number assigned to the first special opcode. <a href="#a821d6d9a98cbab9707c78bf0db7c0989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/contenttypetracker">ContentTypeTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb5cefeb9a45c8c81d8443247f38bc9">ContentTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This tracks which optional file format content types are present. <a href="#addb5cefeb9a45c8c81d8443247f38bc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87642f5889ddcae878af0ca66428b481">StandardOpcodeLengths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e842c839fb74dd8d8500e9ea363da0">IncludeDirectories</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry">FileNameEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a></td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Prologue() {#a6ed4cdb8724ffa55b875906ac41dc7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugLine::Prologue::Prologue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>Reference <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a334b596dc1208300576fc6f81b5b1e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugLine::Prologue::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="#addb5cefeb9a45c8c81d8443247f38bc9">ContentTypes</a>, <a href="#ab8792778480598c24baa65f25722e4f4">DefaultIsStmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a>, <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>, <a href="#a71e842c839fb74dd8d8500e9ea363da0">IncludeDirectories</a>, <a href="#a5a16cb2aaa44e7c4898bdc0bba3faa7b">LineBase</a>, <a href="#a6b88316d7e742255b1073a0911009105">LineRange</a>, <a href="#a0b76c4e63b464e956eec298b0a8057ef">MaxOpsPerInst</a>, <a href="#a1ea7f31bac618b220bfb554614e042a1">MinInstLength</a>, <a href="#a821d6d9a98cbab9707c78bf0db7c0989">OpcodeBase</a>, <a href="#a31f8c3dda3a345a78074012970805463">PrologueLength</a>, <a href="#a47cb66612cc59003c75c67e4d6ae4ab3">SegSelectorSize</a>, <a href="#a87642f5889ddcae878af0ca66428b481">StandardOpcodeLengths</a> and <a href="#ac93c8f0490ca204fc5d763a92fa8eb59">TotalLength</a>.</p>


<p>Referenced by <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a> and <a href="#a6ed4cdb8724ffa55b875906ac41dc7a3">Prologue</a>.</p>

</div>
</div>

### dump() {#a337d62499b18cdbc7fa0a79cc820d09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugLine::Prologue::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOptions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a470b563ab6480d4717a8ca984fe2752c">llvm::DWARFDebugLine::FileNameEntry::Checksum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#addb5cefeb9a45c8c81d8443247f38bc9">ContentTypes</a>, <a href="#ab8792778480598c24baa65f25722e4f4">DefaultIsStmt</a>, <a href="/web-llvm/docs/api/structs/llvm/md5/md5result/#a09ec9cf8d69ac45d9959d3aeb5ec2cce">llvm::MD5::MD5Result::digest</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#ac0c5fbd2279527ccfc0c0ef76c19ddce">llvm::DWARFDebugLine::FileNameEntry::DirIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>, <a href="#a9a106e861c36966e4d25dbb732fc0a7a">getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ae6bcf159d6ccb3adb4f7409e3adbbb37">llvm::DWARFFormValue::getAsCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a71e842c839fb74dd8d8500e9ea363da0">IncludeDirectories</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a1ad164d81f384c7382b578b6d3931e84">llvm::DWARFDebugLine::FileNameEntry::Length</a>, <a href="#a5a16cb2aaa44e7c4898bdc0bba3faa7b">LineBase</a>, <a href="#a6b88316d7e742255b1073a0911009105">LineRange</a>, <a href="#a0b76c4e63b464e956eec298b0a8057ef">MaxOpsPerInst</a>, <a href="#a1ea7f31bac618b220bfb554614e042a1">MinInstLength</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a2cfc2ae9340176e7522776e16aff626b">llvm::DWARFDebugLine::FileNameEntry::ModTime</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a87729f4fadb52e26d3e6b551f476d331">llvm::DWARFDebugLine::FileNameEntry::Name</a>, <a href="#a821d6d9a98cbab9707c78bf0db7c0989">OpcodeBase</a>, <a href="#a31f8c3dda3a345a78074012970805463">PrologueLength</a>, <a href="#a47cb66612cc59003c75c67e4d6ae4ab3">SegSelectorSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a88df681bcf62025e5b46f79d5a9495f1">llvm::DWARFDebugLine::FileNameEntry::Source</a>, <a href="#a87642f5889ddcae878af0ca66428b481">StandardOpcodeLengths</a>, <a href="#ac93c8f0490ca204fc5d763a92fa8eb59">TotalLength</a>, <a href="#a929996e51bac45d53456dacc7b1c4a05">totalLengthIsValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a84b3bf73efd03b0843b88f3c140e8e9e">versionIsSupported</a>.</p>

</div>
</div>

### getAddressSize() {#a9a106e861c36966e4d25dbb732fc0a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::getAddressSize ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>.</p>


<p>Referenced by <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### getFileNameByIndex() {#aa47cad32e9eb34704f1ce2ead863e518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::Prologue::getFileNameByIndex (uint64_t FileIndex, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompDir, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind, std::string &amp; Result, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49f">sys::path::Style</a> Style=<a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">sys::path::Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1448 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="#a9f2e8b7998b275bb9b237db898f67c42">getFileNameEntry</a>, <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>, <a href="#a2815552ca549e1a61b7b87644fafee11">hasFileAtIndex</a>, <a href="#a71e842c839fb74dd8d8500e9ea363da0">IncludeDirectories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#aba60ebbb0330f9e5e713c887d90a40ea">llvm::dwarf_linker::isPathAbsoluteOnWindowsOrPosix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa10731e4d6c303386a70337b0e0668d0">llvm::dwarf::toStringRef</a>.</p>

</div>
</div>

### getFileNameEntry() {#a9f2e8b7998b275bb9b237db898f67c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const llvm::DWARFDebugLine::FileNameEntry &amp; DWARFDebugLine::Prologue::getFileNameEntry (uint64_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get DWARF-version aware access to the file name entry at the provided index.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a> and <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>.</p>


<p>Referenced by <a href="#aa47cad32e9eb34704f1ce2ead863e518">getFileNameByIndex</a>.</p>

</div>
</div>

### getFormParams() {#a6c175233d7f52bbd81d731366a8c5ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const dwarf::FormParams llvm::DWARFDebugLine::Prologue::getFormParams ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>.</p>

</div>
</div>

### getLastValidFileIndex() {#a5b80abc56d98c9368d45aff678818371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugLine::Prologue::getLastValidFileIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a> and <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>.</p>

</div>
</div>

### getLength() {#ad3600be7b74d87cb7ca4f4c55c3982aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFDebugLine::Prologue::getLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Length of the prologue in bytes.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#a31f8c3dda3a345a78074012970805463">PrologueLength</a>, <a href="#a5cf0dc75e536f907bdbec18a48c8adce">sizeofPrologueLength</a> and <a href="#a38113edbada659af2f487d2ceb50c978">sizeofTotalLength</a>.</p>

</div>
</div>

### getVersion() {#a49bbc4647e2aa758e70f85091c87ed0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DWARFDebugLine::Prologue::getVersion ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>.</p>


<p>Referenced by <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="#aa47cad32e9eb34704f1ce2ead863e518">getFileNameByIndex</a>, <a href="#a9f2e8b7998b275bb9b237db898f67c42">getFileNameEntry</a>, <a href="#a5b80abc56d98c9368d45aff678818371">getLastValidFileIndex</a>, <a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">getLength</a>, <a href="#a2815552ca549e1a61b7b87644fafee11">hasFileAtIndex</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### hasFileAtIndex() {#a2815552ca549e1a61b7b87644fafee11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::Prologue::hasFileAtIndex (uint64_t FileIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a> and <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>.</p>


<p>Referenced by <a href="#aa47cad32e9eb34704f1ce2ead863e518">getFileNameByIndex</a>.</p>

</div>
</div>

### isDWARF64() {#a435e877cb6f111a61782d078d4abf796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::Prologue::isDWARF64 ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a> and <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>.</p>


<p>Referenced by <a href="#a5cf0dc75e536f907bdbec18a48c8adce">sizeofPrologueLength</a> and <a href="#a38113edbada659af2f487d2ceb50c978">sizeofTotalLength</a>.</p>

</div>
</div>

### parse() {#a5d63a698aa61a9d04d1826b1f91a0b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFDebugLine::Prologue::parse (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#addb5cefeb9a45c8c81d8443247f38bc9">ContentTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#ab8792778480598c24baa65f25722e4f4">DefaultIsStmt</a>, <a href="#ae0e9b6a6155981551e95dece746694f3">FileNames</a>, <a href="#ad1a98ac8bd44a05c862c20b5963957d4">FormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a>, <a href="#a9a106e861c36966e4d25dbb732fc0a7a">getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a10e13073556511543a885ea96b61ff6c">llvm::DWARFDataExtractor::getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a814a7655e692e4f880b38eed143052fb">llvm::DWARFDataExtractor::getRelocatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a71e842c839fb74dd8d8500e9ea363da0">IncludeDirectories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="#a5a16cb2aaa44e7c4898bdc0bba3faa7b">LineBase</a>, <a href="#a6b88316d7e742255b1073a0911009105">LineRange</a>, <a href="#a0b76c4e63b464e956eec298b0a8057ef">MaxOpsPerInst</a>, <a href="#a1ea7f31bac618b220bfb554614e042a1">MinInstLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="#a821d6d9a98cbab9707c78bf0db7c0989">OpcodeBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a132fc2d4f9a680228706747b8608e269">parseV5DirFileTables</a>, <a href="#a31f8c3dda3a345a78074012970805463">PrologueLength</a>, <a href="#a47cb66612cc59003c75c67e4d6ae4ab3">SegSelectorSize</a>, <a href="#a5cf0dc75e536f907bdbec18a48c8adce">sizeofPrologueLength</a>, <a href="#a87642f5889ddcae878af0ca66428b481">StandardOpcodeLengths</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a3453d69f4b4b74c0cf69808bc7d1c8b0">llvm::DataExtractor::Cursor::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="#ac93c8f0490ca204fc5d763a92fa8eb59">TotalLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a84b3bf73efd03b0843b88f3c140e8e9e">versionIsSupported</a>.</p>

</div>
</div>

### sizeofPrologueLength() {#a5cf0dc75e536f907bdbec18a48c8adce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugLine::Prologue::sizeofPrologueLength ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#a435e877cb6f111a61782d078d4abf796">isDWARF64</a>.</p>


<p>Referenced by <a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">getLength</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### sizeofTotalLength() {#a38113edbada659af2f487d2ceb50c978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugLine::Prologue::sizeofTotalLength ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#a435e877cb6f111a61782d078d4abf796">isDWARF64</a>.</p>


<p>Referenced by <a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">getLength</a>.</p>

</div>
</div>

### totalLengthIsValid() {#a929996e51bac45d53456dacc7b1c4a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::Prologue::totalLengthIsValid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>Reference <a href="#ac93c8f0490ca204fc5d763a92fa8eb59">TotalLength</a>.</p>


<p>Referenced by <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ContentTypes {#addb5cefeb9a45c8c81d8443247f38bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContentTypeTracker llvm::DWARFDebugLine::Prologue::ContentTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This tracks which optional file format content types are present.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### DefaultIsStmt {#ab8792778480598c24baa65f25722e4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::DefaultIsStmt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The initial value of theis_stmtregister.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### FileNames {#ae0e9b6a6155981551e95dece746694f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FileNameEntry&gt; llvm::DWARFDebugLine::Prologue::FileNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="#a9f2e8b7998b275bb9b237db898f67c42">getFileNameEntry</a>, <a href="#a5b80abc56d98c9368d45aff678818371">getLastValidFileIndex</a>, <a href="#a2815552ca549e1a61b7b87644fafee11">hasFileAtIndex</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### FormParams {#ad1a98ac8bd44a05c862c20b5963957d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::FormParams llvm::DWARFDebugLine::Prologue::FormParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Version, address size (starting in v5), and DWARF32/64 format; these parameters affect interpretation of forms (used in the directory and file tables starting with v5).</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#ad43ae71d8137d5a78d559644f17eb162">llvm::dwarf_linker::classic::DwarfStreamer::emitLineTableForUnit</a>, <a href="#a9a106e861c36966e4d25dbb732fc0a7a">getAddressSize</a>, <a href="#a6c175233d7f52bbd81d731366a8c5ed0">getFormParams</a>, <a href="#a49bbc4647e2aa758e70f85091c87ed0e">getVersion</a>, <a href="#a435e877cb6f111a61782d078d4abf796">isDWARF64</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### IncludeDirectories {#a71e842c839fb74dd8d8500e9ea363da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DWARFFormValue&gt; llvm::DWARFDebugLine::Prologue::IncludeDirectories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="#aa47cad32e9eb34704f1ce2ead863e518">getFileNameByIndex</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### LineBase {#a5a16cb2aaa44e7c4898bdc0bba3faa7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int8_t llvm::DWARFDebugLine::Prologue::LineBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This parameter affects the meaning of the special opcodes. See below.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### LineRange {#a6b88316d7e742255b1073a0911009105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::LineRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This parameter affects the meaning of the special opcodes. See below.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### MaxOpsPerInst {#a0b76c4e63b464e956eec298b0a8057ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::MaxOpsPerInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of individual operations that may be encoded in an instruction.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### MinInstLength {#a1ea7f31bac618b220bfb554614e042a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::MinInstLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of the smallest target machine instruction.</p>


<p>Statement program opcodes that alter the address register first multiply their operands by this value.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### OpcodeBase {#a821d6d9a98cbab9707c78bf0db7c0989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::OpcodeBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number assigned to the first special opcode.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### PrologueLength {#a31f8c3dda3a345a78074012970805463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugLine::Prologue::PrologueLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes following the prologue_length field to the beginning of the first byte of the statement program itself.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="#ad3600be7b74d87cb7ca4f4c55c3982aa">getLength</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### SegSelectorSize {#a47cb66612cc59003c75c67e4d6ae4ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFDebugLine::Prologue::SegSelectorSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In v5, size in bytes of a segment selector.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### StandardOpcodeLengths {#a87642f5889ddcae878af0ca66428b481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint8_t&gt; llvm::DWARFDebugLine::Prologue::StandardOpcodeLengths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a> and <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a>.</p>

</div>
</div>

### TotalLength {#ac93c8f0490ca204fc5d763a92fa8eb59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugLine::Prologue::TotalLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size in bytes of the statement information for this compilation unit (not including the total_length field itself).</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a334b596dc1208300576fc6f81b5b1e90">clear</a>, <a href="#a337d62499b18cdbc7fa0a79cc820d09b">dump</a>, <a href="#a5d63a698aa61a9d04d1826b1f91a0b43">parse</a> and <a href="#a929996e51bac45d53456dacc7b1c4a05">totalLengthIsValid</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
