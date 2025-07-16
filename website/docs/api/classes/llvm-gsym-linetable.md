---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/linetable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LineTable` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> class contains deserialized versions of line tables for each function's address ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::gsym::LineTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">llvm/DebugInfo/GSYM/LineTable.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">gsym::LineEntry</a> &gt; <a href="#af25a12a71512acf7a5a97a056a385423">Collection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab990738ca07fca98fb5cbf4dc47f8917">operator[]</a> (size_t i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab506aa5ef834c571ce43d6dc74838272">operator[]</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e120191429c9e3cf0044a6f0cf26bd9">operator==</a> (const LineTable &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e709ed389aaf92b2206ff6d0903521">operator!=</a> (const LineTable &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2099d6ab7cf0271c0acd2dd1118fc1">operator&lt;</a> (const LineTable &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c4a2acdbcfaf2a18a61b60d42a9dc4">encode</a> (FileWriter &amp;O, uint64_t BaseAddr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#a41c4a2acdbcfaf2a18a61b60d42a9dc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217bee3953337d99533f6683f7950af3">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484474b41779995f4f3456843e60b415">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a0913f724310afc36be1408fa57856">first</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first line entry if the line table isn't empty. <a href="#ad4a0913f724310afc36be1408fa57856">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd2491a276829c6fc65a1c8efba65b1">last</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last line entry if the line table isn't empty. <a href="#a2bd2491a276829c6fc65a1c8efba65b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe621e467048c0813e3fc66b832c906">push</a> (const LineEntry &amp;LE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abada6578389b8ebe5ade2c69fbc67b02">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a631a78ed3f47224a14d2e391208ef5">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a2722f6595b429275a76e8a0152366">get</a> (size_t i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9030fbde393b57bd09a081845dcb2158">get</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Collection::const_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119cd252e6fc513ba5c9d70c025bd52c">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Collection::const_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b37505e8ebfa0e0f45dc0c9eb3a8206">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Collection</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e12f091ad0ba1c5318adfdeb4d1fd3c">Lines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All line entries in the line table. <a href="#a2e12f091ad0ba1c5318adfdeb4d1fd3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bca453dce01051bae3751cbb4d14fef">lookup</a> (DataExtractor &amp;Data, uint64_t BaseAddr, uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup a single address within a line table's data. <a href="#a9bca453dce01051bae3751cbb4d14fef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c433311387761ffb00f0aea6be6675">decode</a> (DataExtractor &amp;Data, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object from a binary data stream. <a href="#a45c433311387761ffb00f0aea6be6675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> class contains deserialized versions of line tables for each function's address ranges.</p>


<p>When saved to disk, the line table is encoded using a modified version of the DWARF line tables that only tracks address to source file and line.</p>


<p>ENCODING</p>


<p>The line table starts with a small prolog that contains the following values:</p>


<p>ENCODING NAME DESCRIPTION ======== =========== ==================================================== SLEB MinDelta The min line delta for special opcodes that advance the address and line number. SLEB MaxDelta The max line delta for single byte opcodes that advance the address and line number. ULEB FirstLine The value of the first source line number to initialize the <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> with.</p>


<p>Once these prolog items are read, we initialize a <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> struct with the start address of the function from the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s address range, a default file index of 1, and the line number set to "FirstLine" from the prolog above:</p>


<p><a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> Row(BaseAddr, 1, FirstLine);</p>


<p>The line table state machine is now initialized and ready to be parsed. The stream that follows this encodes the line entries in a compact form. Some opcodes cause "Row" to be modified and some opcodes may also push "Row" onto the end of the "LineTable.Lines" vector. The end result is a vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> structs that is sorted in ascending address order.</p>


<p>NORMAL OPCODES</p>


<p>The opcodes 0 through 3 are normal in opcodes. Their encoding and descriptions are listed below:</p>


<p>ENCODING ENUMERATION VALUE DESCRIPTION ======== ================ ===== ======================================== LTOC_EndSequence 0x00 Parsing is done. ULEB LTOC_SetFile 0x01 Row.File = ULEB ULEB LTOC_AdvancePC 0x02 Row.Addr += ULEB, push "Row". SLEB LTOC_AdvanceLine 0x03 Row.Line += SLEB LTOC_FirstSpecial 0x04 First special opcode (see SPECIAL OPCODES below).</p>


<p>SPECIAL OPCODES</p>


<p>Opcodes LTOC_FirstSpecial through 255 are special opcodes that always increment both the Row.Addr and Row.Line and push "Row" onto the LineEntry.Lines array. They do this by using some of the bits to increment/decrement the source line number, and some of the bits to increment the address. Line numbers can go up or down when making line tables, where addresses always only increase since line tables are sorted by address.</p>


<p>In order to calculate the amount to increment the line and address for these special opcodes, we calculate the number of values reserved for the line increment/decrement using the "MinDelta" and "MaxDelta" from the prolog:</p>



<pre><code>const int64_t LineRange = MaxDelta - MinDelta + 1;
</code></pre>


<p>Then we can adjust the opcode to not include any of the normal opcodes:</p>



<pre><code>const uint8_t AdjustedOp = Opcode - LTOC_FirstSpecial;
</code></pre>


<p>And we can calculate the line offset, and address offset:</p>



<pre><code>const int64_t LineDelta = MinDelta + (AdjustedOp % LineRange);
const uint64_t AddrDelta = (AdjustedOp / LineRange);
</code></pre>


<p>And use these to modify our "Row":</p>



<pre><code>Row.Line += LineDelta;
Row.Addr += AddrDelta;
</code></pre>


<p>And push a row onto the line table:</p>



<pre><code>Lines.push_back(Row);
</code></pre>


<p>This is verify similar to the way that DWARF encodes its line tables. The only difference is the DWARF line tables have more normal opcodes and the "Row" contains more members, like source column number, bools for end of prologue, beginnging of epilogue, is statement and many others. There are also more complex rules that happen for the extra normal opcodes. By leaving these extra opcodes out, we leave more bits for the special opcodes that allows us to encode line tables in fewer bytes than standard DWARF encodings.</p>


<p>Opcodes that will push "Row" onto the LineEntry.Lines include the LTOC_AdvancePC opcode and all special opcodes. All other opcodes only modify the current "Row", or cause the line table to end.</p>


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Collection {#af25a12a71512acf7a5a97a056a385423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;gsym::LineEntry&gt; llvm::gsym::LineTable::Collection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#af0e709ed389aaf92b2206ff6d0903521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::LineTable::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &amp; RHS)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\[\]() {#ab990738ca07fca98fb5cbf4dc47f8917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineEntry &amp; llvm::gsym::LineTable::operator[] (size_t i)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="#ad0a2722f6595b429275a76e8a0152366">get</a>.</p>

</div>
</div>

### operator\[\]() {#ab506aa5ef834c571ce43d6dc74838272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LineEntry &amp; llvm::gsym::LineTable::operator[] (size_t i)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="#ad0a2722f6595b429275a76e8a0152366">get</a>.</p>

</div>
</div>

### operator&lt;() {#abb2099d6ab7cf0271c0acd2dd1118fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::LineTable::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &amp; RHS)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a0e120191429c9e3cf0044a6f0cf26bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::LineTable::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &amp; RHS)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a119cd252e6fc513ba5c9d70c025bd52c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::gsym::LineTable::begin ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### clear() {#a484474b41779995f4f3456843e60b415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::LineTable::clear ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### empty() {#a217bee3953337d99533f6683f7950af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::LineTable::empty ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### encode() {#a41c4a2acdbcfaf2a18a61b60d42a9dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error LineTable::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O, uint64_t BaseAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to at the current file position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding the line table. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure or the encoding process.</p></dd>
</dl>


<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry/#abf4509caa6884e20728dd5b8e08b925a">llvm::gsym::LineEntry::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a90de7cef943238ae1b541e31b373ed68ad70cf2d6845766439609f1cd17b9609c">AdvanceLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a90de7cef943238ae1b541e31b373ed68afdf828b840cddca16f427cc3f2b72fac">AdvancePC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#ad9cd4a2e1984be7b783ac9bb124fa83b">encodeSpecial</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a90de7cef943238ae1b541e31b373ed68afd55184035d28c16fb83e0a80ecd57a6">EndSequence</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry/#a193c4a1af11b83092b6db93d02219b1e">llvm::gsym::LineEntry::File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ab21f12f372f67b8ff0aa3432336ede67">INT64_MIN</a>, <a href="#abada6578389b8ebe5ade2c69fbc67b02">isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry/#a7648b354c70ebeac2fa9001116b84d11">llvm::gsym::LineEntry::Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a90de7cef943238ae1b541e31b373ed68a814ad7183f3b1f1aafd5d82aeef1e44d">SetFile</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a3d4ccfc2f70d9b024d7489a9e943389e">llvm::gsym::FileWriter::writeSLEB</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a45e4989cbade2289d6496aa80c97a748">llvm::gsym::FileWriter::writeU8</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a155ed5ec938a9850383cdd2db34cbd32">llvm::gsym::FileWriter::writeULEB</a>.</p>

</div>
</div>

### end() {#a2b37505e8ebfa0e0f45dc0c9eb3a8206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::gsym::LineTable::end ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### first() {#ad4a0913f724310afc36be1408fa57856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LineEntry &gt; llvm::gsym::LineTable::first ()</td>
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

<p>Return the first line entry if the line table isn't empty.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional line entry with the first line entry if the line table isn't empty, or std::nullopt if the line table is emtpy.</p></dd>
</dl>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### get() {#ad0a2722f6595b429275a76e8a0152366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineEntry &amp; llvm::gsym::LineTable::get (size_t i)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ab990738ca07fca98fb5cbf4dc47f8917">operator[]</a> and <a href="#ab506aa5ef834c571ce43d6dc74838272">operator[]</a>.</p>

</div>
</div>

### get() {#a9030fbde393b57bd09a081845dcb2158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LineEntry &amp; llvm::gsym::LineTable::get (size_t i)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### isValid() {#abada6578389b8ebe5ade2c69fbc67b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::gsym::LineTable::isValid ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>


<p>Referenced by <a href="#a41c4a2acdbcfaf2a18a61b60d42a9dc4">encode</a>.</p>

</div>
</div>

### last() {#a2bd2491a276829c6fc65a1c8efba65b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LineEntry &gt; llvm::gsym::LineTable::last ()</td>
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

<p>Return the last line entry if the line table isn't empty.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional line entry with the last line entry if the line table isn't empty, or std::nullopt if the line table is emtpy.</p></dd>
</dl>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### push() {#a1fe621e467048c0813e3fc66b832c906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::LineTable::push (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp; LE)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

### size() {#a7a631a78ed3f47224a14d2e391208ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::gsym::LineTable::size ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Lines {#a2e12f091ad0ba1c5318adfdeb4d1fd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection llvm::gsym::LineTable::Lines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All line entries in the line table.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#a45c433311387761ffb00f0aea6be6675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; LineTable &gt; LineTable::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr)</td>
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

<p>Decode an <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding the line table. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address and will be used to initialize the line table row prior to parsing any opcodes.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a45e99fb329714d8911cb5e116eb8a3bc">parse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a>.</p>

</div>
</div>

### lookup() {#a9bca453dce01051bae3751cbb4d14fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; LineEntry &gt; LineTable::lookup (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr, uint64_t Addr)</td>
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

<p>Lookup a single address within a line table's data.</p>


<p>Clients have the option to decode an entire line table using <a href="#a45c433311387761ffb00f0aea6be6675">LineTable::decode()</a> or just find a single matching entry using this function. The benefit of using this function is that parsed <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> objects that do not match will not be stored in an array. This will avoid memory allocation costs and parsing can stop once a match has been found.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding the line table. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address and will be used to initialize the line table row prior to parsing any opcodes.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> object if a match is found, error otherwise.</p></dd>
</dl>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp/#a45e99fb329714d8911cb5e116eb8a3bc">parse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">LineTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
