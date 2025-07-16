---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stackmapparser/recordaccessor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RecordAccessor` Class Reference

<p>Accessor for stackmap records. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StackMapParser::RecordAccessor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">llvm/Object/StackMapParser.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c6401565461f93288f62495a4f2e13">location_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/stackmapparser/accessoriterator">AccessorIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stackmapparser/locationaccessor">LocationAccessor</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97f5f4d3009d663a3849ab6141651656">liveout_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/stackmapparser/accessoriterator">AccessorIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stackmapparser/liveoutaccessor">LiveOutAccessor</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17f958c0becb741446f280dc6fb409d">StackMapParser</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56224669d8c42f88c7f331d5beffa9ac">RecordAccessor</a> (const uint8_t *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7da9ec37ed73ca4e6765041da5df4cc">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the patchpoint/stackmap <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this record. <a href="#ad7da9ec37ed73ca4e6765041da5df4cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2fba4a554319c94d2f533c19d430c1">getInstructionOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction offset (from the start of the containing function) for this record. <a href="#a4c2fba4a554319c94d2f533c19d430c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243a25746d1216a7dfcead20aa138453">getNumLocations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of locations contained in this record. <a href="#a243a25746d1216a7dfcead20aa138453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackmapparser/locationaccessor">LocationAccessor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b9c79feaad9ce930ff1c74e24448b9">getLocation</a> (unsigned LocationIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the location with the given index. <a href="#a41b9c79feaad9ce930ff1c74e24448b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad1c6401565461f93288f62495a4f2e13">location_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7cd90a857ae4a5c15bad9d21e3447c5">location_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin iterator for locations. <a href="#ad7cd90a857ae4a5c15bad9d21e3447c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad1c6401565461f93288f62495a4f2e13">location_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41b0f04c0e086c9d0d2fdef95550ecd">location_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End iterator for locations. <a href="#af41b0f04c0e086c9d0d2fdef95550ecd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad1c6401565461f93288f62495a4f2e13">location_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813e397f6810e4065adefe188e26b713">locations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator range for locations. <a href="#a813e397f6810e4065adefe188e26b713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0d0a001aaed9485c329dcc0aaf0a9d">getNumLiveOuts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of liveouts contained in this record. <a href="#adc0d0a001aaed9485c329dcc0aaf0a9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackmapparser/liveoutaccessor">LiveOutAccessor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0ac72b0b406939e6bcf4c6bc29666a">getLiveOut</a> (unsigned LiveOutIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the live-out with the given index. <a href="#a8c0ac72b0b406939e6bcf4c6bc29666a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97f5f4d3009d663a3849ab6141651656">liveout_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6fc41f4d519434d665ca1094d84667">liveouts_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin iterator for live-outs. <a href="#aee6fc41f4d519434d665ca1094d84667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97f5f4d3009d663a3849ab6141651656">liveout_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e509b290a185598e496797b44b4af58">liveouts_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End iterator for live-outs. <a href="#a5e509b290a185598e496797b44b4af58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a97f5f4d3009d663a3849ab6141651656">liveout_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8972b9ee381f9db9e773e80e24cb56">liveouts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator range for live-outs. <a href="#a0f8972b9ee381f9db9e773e80e24cb56">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8858cf32492771495fde3b5cad47b9e">getNumLiveOutsOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c7779a2da99ddee6f332aa8fd828ee">getSizeInBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackmapparser/recordaccessor">RecordAccessor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71193313f1dc58a8cd89de1fc1c20e3">next</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7265faf05da21fa9599778605b6d0d8">P</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74635d9252ab6a304a4b370e5fd4f25a">PatchpointIDOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60aed1dd1227d4ea9b8419005b0b8c2">InstructionOffsetOffset</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6a0b3c67c9a39b8437ec1237beb2e2">NumLocationsOffset</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26df6a840096db81bd7006d1dbb8a894">LocationListOffset</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a720c9ca4e51bb661b0b90301dee552">LocationSize</a> = sizeof(uint64_t) + sizeof(uint32_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c17410463e2746686197e09c6dec8a">LiveOutSize</a> = sizeof(uint32_t)</td>
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

<p>Accessor for stackmap records.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### liveout\_iterator {#a97f5f4d3009d663a3849ab6141651656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveout_iterator =  AccessorIterator&lt;LiveOutAccessor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### location\_iterator {#ad1c6401565461f93288f62495a4f2e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_iterator =  AccessorIterator&lt;LocationAccessor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### StackMapParser {#ad17f958c0becb741446f280dc6fb409d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/stackmapparser">StackMapParser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Reference <a href="#ad17f958c0becb741446f280dc6fb409d">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::StackMapParser</a>.</p>


<p>Referenced by <a href="#ad17f958c0becb741446f280dc6fb409d">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::StackMapParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RecordAccessor() {#a56224669d8c42f88c7f331d5beffa9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::RecordAccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * P)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getID() {#ad7da9ec37ed73ca4e6765041da5df4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getID ()</td>
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

<p>Get the patchpoint/stackmap <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this record.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### getInstructionOffset() {#a4c2fba4a554319c94d2f533c19d430c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getInstructionOffset ()</td>
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

<p>Get the instruction offset (from the start of the containing function) for this record.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### getLiveOut() {#a8c0ac72b0b406939e6bcf4c6bc29666a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveOutAccessor llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLiveOut (unsigned LiveOutIndex)</td>
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

<p>Get the live-out with the given index.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Referenced by <a href="#aee6fc41f4d519434d665ca1094d84667">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_begin</a> and <a href="#a5e509b290a185598e496797b44b4af58">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_end</a>.</p>

</div>
</div>

### getLocation() {#a41b9c79feaad9ce930ff1c74e24448b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationAccessor llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLocation (unsigned LocationIndex)</td>
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

<p>Get the location with the given index.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Referenced by <a href="#ad7cd90a857ae4a5c15bad9d21e3447c5">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_begin</a> and <a href="#af41b0f04c0e086c9d0d2fdef95550ecd">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_end</a>.</p>

</div>
</div>

### getNumLiveOuts() {#adc0d0a001aaed9485c329dcc0aaf0a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getNumLiveOuts ()</td>
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

<p>Get the number of liveouts contained in this record.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Referenced by <a href="#a5e509b290a185598e496797b44b4af58">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_end</a>.</p>

</div>
</div>

### getNumLocations() {#a243a25746d1216a7dfcead20aa138453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getNumLocations ()</td>
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

<p>Get the number of locations contained in this record.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Referenced by <a href="#af41b0f04c0e086c9d0d2fdef95550ecd">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_end</a>.</p>

</div>
</div>

### liveouts() {#a0f8972b9ee381f9db9e773e80e24cb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; liveout_iterator &gt; llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts ()</td>
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

<p>Iterator range for live-outs.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>References <a href="#aee6fc41f4d519434d665ca1094d84667">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_begin</a>, <a href="#a5e509b290a185598e496797b44b4af58">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### liveouts\_begin() {#aee6fc41f4d519434d665ca1094d84667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">liveout_iterator llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_begin ()</td>
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

<p>Begin iterator for live-outs.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Reference <a href="#a8c0ac72b0b406939e6bcf4c6bc29666a">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLiveOut</a>.</p>


<p>Referenced by <a href="#a0f8972b9ee381f9db9e773e80e24cb56">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts</a>.</p>

</div>
</div>

### liveouts\_end() {#a5e509b290a185598e496797b44b4af58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">liveout_iterator llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts_end ()</td>
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

<p>End iterator for live-outs.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>References <a href="#a8c0ac72b0b406939e6bcf4c6bc29666a">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLiveOut</a> and <a href="#adc0d0a001aaed9485c329dcc0aaf0a9d">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getNumLiveOuts</a>.</p>


<p>Referenced by <a href="#a0f8972b9ee381f9db9e773e80e24cb56">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::liveouts</a>.</p>

</div>
</div>

### location\_begin() {#ad7cd90a857ae4a5c15bad9d21e3447c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">location_iterator llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_begin ()</td>
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

<p>Begin iterator for locations.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>Reference <a href="#a41b9c79feaad9ce930ff1c74e24448b9">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLocation</a>.</p>


<p>Referenced by <a href="#a813e397f6810e4065adefe188e26b713">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::locations</a>.</p>

</div>
</div>

### location\_end() {#af41b0f04c0e086c9d0d2fdef95550ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">location_iterator llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_end ()</td>
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

<p>End iterator for locations.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>References <a href="#a41b9c79feaad9ce930ff1c74e24448b9">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getLocation</a> and <a href="#a243a25746d1216a7dfcead20aa138453">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getNumLocations</a>.</p>


<p>Referenced by <a href="#a813e397f6810e4065adefe188e26b713">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::locations</a>.</p>

</div>
</div>

### locations() {#a813e397f6810e4065adefe188e26b713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; location_iterator &gt; llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::locations ()</td>
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

<p>Iterator range for locations.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>


<p>References <a href="#ad7cd90a857ae4a5c15bad9d21e3447c5">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_begin</a>, <a href="#af41b0f04c0e086c9d0d2fdef95550ecd">llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::location_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNumLiveOutsOffset() {#ac8858cf32492771495fde3b5cad47b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getNumLiveOutsOffset ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### getSizeInBytes() {#a45c7779a2da99ddee6f332aa8fd828ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::getSizeInBytes ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### next() {#ac71193313f1dc58a8cd89de1fc1c20e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordAccessor llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::next ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### P {#ae7265faf05da21fa9599778605b6d0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t* llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### InstructionOffsetOffset {#ab60aed1dd1227d4ea9b8419005b0b8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::InstructionOffsetOffset</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      PatchpointIDOffset + sizeof(uint64_t)
</div>
</dd>
</dl>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### LiveOutSize {#ac5c17410463e2746686197e09c6dec8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::LiveOutSize = sizeof(uint32_t)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### LocationListOffset {#a26df6a840096db81bd7006d1dbb8a894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::LocationListOffset</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      NumLocationsOffset + sizeof(uint16_t)
</div>
</dd>
</dl>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### LocationSize {#a7a720c9ca4e51bb661b0b90301dee552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::LocationSize = sizeof(uint64_t) + sizeof(uint32_t)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### NumLocationsOffset {#a4a6a0b3c67c9a39b8437ec1237beb2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::NumLocationsOffset</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      InstructionOffsetOffset + sizeof(uint32_t) + sizeof(uint16_t)
</div>
</dd>
</dl>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

### PatchpointIDOffset {#a74635d9252ab6a304a4b370e5fd4f25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::StackMapParser&lt; Endianness &gt;::RecordAccessor::PatchpointIDOffset = 0</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/stackmapparser-h">StackMapParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
