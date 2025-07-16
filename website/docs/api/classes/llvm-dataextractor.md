---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dataextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DataExtractor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DataExtractor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> (typically for an in-memory copy of an object-file section) plus a relocation map for that section, if there is one. <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46aa25f9df530608164c58934b2c5f01">DataExtractor</a> (StringRef Data, bool IsLittleEndian, uint8_t AddressSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct with a buffer that is owned by the caller. <a href="#a46aa25f9df530608164c58934b2c5f01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80db7425f3e992ef519e25179f94fb56">DataExtractor</a> (ArrayRef&lt; uint8_t &gt; Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882aa042b8549998c9ae43305a79d955">getData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data pointed to by this extractor. <a href="#a882aa042b8549998c9ae43305a79d955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9617bd42a629b75a6804af2cbcddddf">isLittleEndian</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the endianness for this extractor. <a href="#ad9617bd42a629b75a6804af2cbcddddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727b157e8418a101ec69dcb2e9ceea39">getAddressSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address size for this extractor. <a href="#a727b157e8418a101ec69dcb2e9ceea39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f5d1feac4b501f815939a0ca847d41">setAddressSize</a> (uint8_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the address size for this extractor. <a href="#ad1f5d1feac4b501f815939a0ca847d41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17638a9e9146a6f6feef1adb50c53d2b">getCStr</a> (uint64_t *OffsetPtr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a C string from <em>*offset_ptr</em>. <a href="#a17638a9e9146a6f6feef1adb50c53d2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98013dfe461d03c79996aa701959af99">getCStr</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a C string from the location given by the cursor. <a href="#a98013dfe461d03c79996aa701959af99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b587fe584a4e8b02c4ca0426be42918">getCStrRef</a> (uint64_t *OffsetPtr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a C string from <em>*offset_ptr</em>. <a href="#a3b587fe584a4e8b02c4ca0426be42918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a63167c274c9f88ebe28d65a62b5109">getCStrRef</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a C string (as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) from the location given by the cursor. <a href="#a8a63167c274c9f88ebe28d65a62b5109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01226a387955cebb0a2a163395a8a527">getFixedLengthString</a> (uint64_t *OffsetPtr, uint64_t Length, StringRef TrimChars={"\0", 1}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a fixed length string from <em>*OffsetPtr</em> and consume <em>Length</em> bytes. <a href="#a01226a387955cebb0a2a163395a8a527">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9e119455709c0d46a34464ebdbf179">getBytes</a> (uint64_t *OffsetPtr, uint64_t Length, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a fixed number of bytes from the specified offset. <a href="#ade9e119455709c0d46a34464ebdbf179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fbdc9c7fff080e339590ef1729e9e2e">getBytes</a> (Cursor &amp;C, uint64_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a fixed number of bytes from the location given by the cursor. <a href="#a8fbdc9c7fff080e339590ef1729e9e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a> (uint64_t *offset_ptr, uint32_t byte_size, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an unsigned integer of size <em>byte_size</em> from <em>*offset_ptr</em>. <a href="#a091e3b172c8f532c021b21c90fd3d461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e826702732f1904f880287c57de1050">getUnsigned</a> (Cursor &amp;C, uint32_t Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an unsigned integer of the given size from the location given by the cursor. <a href="#a7e826702732f1904f880287c57de1050">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc53bb122d7af1e40b77867d080114d">getSigned</a> (uint64_t *offset_ptr, uint32_t size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an signed integer of size <em>byte_size</em> from <em>*offset_ptr</em>. <a href="#a5cc53bb122d7af1e40b77867d080114d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d94746913373f82219a1d23e15ce31">getAddress</a> (uint64_t *offset_ptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an pointer from <em>*offset_ptr</em>. <a href="#a41d94746913373f82219a1d23e15ce31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade513e9d1a65b9918756e4d2af05228a">getAddress</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a pointer-sized unsigned integer from the location given by the cursor. <a href="#ade513e9d1a65b9918756e4d2af05228a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ee696c4102751e0194a0210c07dac0">getU8</a> (uint64_t *offset_ptr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a uint8_t value from <em>*offset_ptr</em>. <a href="#a45ee696c4102751e0194a0210c07dac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acceb9d609466ce185f4d62cea308cf06">getU8</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a single uint8_t value from the location given by the cursor. <a href="#acceb9d609466ce185f4d62cea308cf06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99714e6728aec45a983ebaa1e3a759b4">getU8</a> (uint64_t *offset_ptr, uint8_t *dst, uint32_t count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>count</em> uint8_t values from <em>*offset_ptr</em>. <a href="#a99714e6728aec45a983ebaa1e3a759b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410f6a91c0a8365d3be5010048789fa0">getU8</a> (Cursor &amp;C, uint8_t *Dst, uint32_t Count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>Count</em> uint8_t values from the location given by the cursor and store them into the destination buffer. <a href="#a410f6a91c0a8365d3be5010048789fa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8968c4c97aefde2610f274d34d6c96">getU8</a> (Cursor &amp;C, SmallVectorImpl&lt; uint8_t &gt; &amp;Dst, uint32_t Count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>Count</em> uint8_t values from the location given by the cursor and store them into the destination vector. <a href="#a1c8968c4c97aefde2610f274d34d6c96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98923ce73981e5171ef246bdcc6fde60">getU16</a> (uint64_t *offset_ptr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a uint16_t value from <em>*offset_ptr</em>. <a href="#a98923ce73981e5171ef246bdcc6fde60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02ab439560d1a46c00cdcdf684d8bb3">getU16</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a single uint16_t value from the location given by the cursor. <a href="#aa02ab439560d1a46c00cdcdf684d8bb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a968738e950c817a5c90ebdb5adeaff08">getU16</a> (uint64_t *offset_ptr, uint16_t *dst, uint32_t count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>count</em> uint16_t values from <em>*offset_ptr</em>. <a href="#a968738e950c817a5c90ebdb5adeaff08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76306ed98218d7cb53f099c42c0dbef">getU24</a> (uint64_t *OffsetPtr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a 24-bit unsigned value from <em>*offset_ptr</em> and return it in a uint32_t. <a href="#ae76306ed98218d7cb53f099c42c0dbef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80037e67b2902789a9092c21e141228d">getU24</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a single 24-bit unsigned value from the location given by the cursor. <a href="#a80037e67b2902789a9092c21e141228d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb55ea3f585f9c8a2619fe7250e56f4">getU32</a> (uint64_t *offset_ptr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a uint32_t value from <em>*offset_ptr</em>. <a href="#a0eb55ea3f585f9c8a2619fe7250e56f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0779b218e615507e5be219472244ecf9">getU32</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a single uint32_t value from the location given by the cursor. <a href="#a0779b218e615507e5be219472244ecf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b99b78638b6b9f381619b62b32afef3">getU32</a> (uint64_t *offset_ptr, uint32_t *dst, uint32_t count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>count</em> uint32_t values from <em>*offset_ptr</em>. <a href="#a2b99b78638b6b9f381619b62b32afef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c91465e0d075f5fc1bdc895c8a5f07">getU64</a> (uint64_t *offset_ptr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a uint64_t value from <em>*offset_ptr</em>. <a href="#ac7c91465e0d075f5fc1bdc895c8a5f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ffbd42e93818f0130cacaba3b5b431">getU64</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a single uint64_t value from the location given by the cursor. <a href="#ab2ffbd42e93818f0130cacaba3b5b431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8a77c19e55900e7e234db43a439dd7">getU64</a> (uint64_t *offset_ptr, uint64_t *dst, uint32_t count) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <em>count</em> uint64_t values from <em>*offset_ptr</em>. <a href="#aac8a77c19e55900e7e234db43a439dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a902fb0c1d600e6b4fe880d770acdf">getSLEB128</a> (uint64_t *OffsetPtr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a signed LEB128 value from <em>*offset_ptr</em>. <a href="#a88a902fb0c1d600e6b4fe880d770acdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2642cbf3b909efa5f4c9033168236ef2">getSLEB128</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an signed LEB128 value from the location given by the cursor. <a href="#a2642cbf3b909efa5f4c9033168236ef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2f68613d44758a66e49320fb075a02">getULEB128</a> (uint64_t *offset_ptr, llvm::Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a unsigned LEB128 value from <em>*offset_ptr</em>. <a href="#a6f2f68613d44758a66e49320fb075a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f7cc5ebb4d6cf752224083a2eeea150">getULEB128</a> (Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an unsigned LEB128 value from the location given by the cursor. <a href="#a7f7cc5ebb4d6cf752224083a2eeea150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c4043f99a1a5b283741ef4c7cf2464">skip</a> (Cursor &amp;C, uint64_t Length) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance the <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> position by the given number of bytes. <a href="#aa4c4043f99a1a5b283741ef4c7cf2464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad190d933f6858fe3437ccf63bf8b65">eof</a> (const Cursor &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff the cursor is at the end of the buffer, regardless of the error state of the cursor. <a href="#a3ad190d933f6858fe3437ccf63bf8b65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c780b958be0ededd6a525ce67206bb">isValidOffset</a> (uint64_t offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test the validity of <em>offset</em>. <a href="#ad6c780b958be0ededd6a525ce67206bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e3a2f9134fa59a38cc0a86acaaf351">isValidOffsetForDataOfSize</a> (uint64_t offset, uint64_t length) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test the availability of <em>length</em> bytes of data from <em>offset</em>. <a href="#ad7e3a2f9134fa59a38cc0a86acaaf351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdae60c28acfc86e2832ade183d3bc27">isValidOffsetForAddress</a> (uint64_t offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test the availability of enough bytes of data for a pointer from <em>offset</em>. <a href="#afdae60c28acfc86e2832ade183d3bc27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f08bc0715c6ccbe15c82f2fc9e61ca">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes in the underlying buffer. <a href="#a13f08bc0715c6ccbe15c82f2fc9e61ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55fe6963d08fd0255315215d1d048ad">prepareRead</a> (uint64_t Offset, uint64_t Size, Error *E) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If it is possible to read <em>Size</em> bytes at offset <em>Offset</em>, returns <b>true</b>. <a href="#ad55fe6963d08fd0255315215d1d048ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc1752dc72b3507aa7a89716da308345">getU</a> (uint64_t *OffsetPtr, Error *Err) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ed23b841961784abeec8f564ca66a97">getUs</a> (uint64_t *OffsetPtr, T *Dst, uint32_t Count, Error *Err) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4addaff512e4efcc676c1da4fc573ed4">Data</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b6ce5073dcad5adca0a3199328229a">IsLittleEndian</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f7e64a18be7b976ba64d99addbfee3">AddressSize</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f74888abb46158e0f6ddec827c36922">getOffset</a> (Cursor &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45d3690fa998e1a63931de09ff05bdc">getError</a> (Cursor &amp;C)</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DataExtractor() {#a46aa25f9df530608164c58934b2c5f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DataExtractor::DataExtractor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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

<p>Construct with a buffer that is owned by the caller.</p>


<p>This constructor allows us to use data that is owned by the caller. The data must stay around as long as this object is valid.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a9c4e8cde73237ab00ac91c380ff95f38">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a7a9a9bc490d816bb7e08cb0eca3b54ae">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a38eb941ecccfee736a78a034bf5b0832">llvm::DWARFDataExtractor::DWARFDataExtractor</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a45ecaa1a4ce76a3cb0a3b5f3b48ea587">llvm::DWARFDataExtractor::DWARFDataExtractor</a>.</p>

</div>
</div>

### DataExtractor() {#a80db7425f3e992ef519e25179f94fb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DataExtractor::DataExtractor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="#a13f08bc0715c6ccbe15c82f2fc9e61ca">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eof() {#a3ad190d933f6858fe3437ccf63bf8b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataExtractor::eof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Return true iff the cursor is at the end of the buffer, regardless of the error state of the cursor.</p>


<p>The only way both eof and error states can be true is if one attempts a read while the cursor is at the very end of the data buffer.</p>


<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a13f08bc0715c6ccbe15c82f2fc9e61ca">size</a>.</p>

</div>
</div>

### getAddress() {#a41d94746913373f82219a1d23e15ce31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::getAddress (uint64_t * offset_ptr)</td>
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

<p>Extract an pointer from <em>*offset_ptr</em>.</p>


<p>Extract a single pointer from the data and update the offset pointed to by <em>offset_ptr</em>. The size of the extracted pointer is <em><a href="#a727b157e8418a101ec69dcb2e9ceea39">getAddressSize()</a></em>, so the address size has to be set correctly prior to extracting any pointer values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted pointer value as a 64 integer.</p></dd>
</dl>


<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>.</p>

</div>
</div>

### getAddress() {#ade513e9d1a65b9918756e4d2af05228a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::getAddress (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a pointer-sized unsigned integer from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>.</p>

</div>
</div>

### getAddressSize() {#a727b157e8418a101ec69dcb2e9ceea39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DataExtractor::getAddressSize ()</td>
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

<p>Get the address size for this extractor.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a7a9a9bc490d816bb7e08cb0eca3b54ae">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#ab0ceb7476c6b212e0f515e2a4cc9e551">llvm::DWARFDataExtractor::getEncodedPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a048e04c3ab40f799fd7e530b1be61f6a">llvm::DWARFDataExtractor::getRelocatedAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a01887ce3b95212d5c5b89887c93ad662">llvm::DWARFDataExtractor::getRelocatedAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>.</p>

</div>
</div>

### getBytes() {#ade9e119455709c0d46a34464ebdbf179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DataExtractor::getBytes (uint64_t * OffsetPtr, uint64_t Length, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a fixed number of bytes from the specified offset.</p>


<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the bytes from the data at the offset pointed to by <em>OffsetPtr</em>. A fixed length C string will be extracted and the <em>OffsetPtr</em> will be advanced by <em>Length</em> bytes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Length</td>
<td class="doxyParamItemDescription"><p>The number of bytes to extract. If there are not enough bytes in the data to extract all of the bytes, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the extracted bytes. If the offset pointed to by <em>OffsetPtr</em> is out of bounds, or if the offset plus the length is out of bounds, a default-initialized <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> will be returned.</p></dd>
</dl>


<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#ac2a4c7453cbb40de6ef58bfe778554cb">isError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>, <a href="#a8fbdc9c7fff080e339590ef1729e9e2e">getBytes</a>, <a href="#a01226a387955cebb0a2a163395a8a527">getFixedLengthString</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>.</p>

</div>
</div>

### getBytes() {#a8fbdc9c7fff080e339590ef1729e9e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataExtractor::getBytes (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint64_t Length)</td>
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

<p>Extract a fixed number of bytes from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, a default-initialized <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> is returned.</p>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ade9e119455709c0d46a34464ebdbf179">getBytes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### getCStr() {#a17638a9e9146a6f6feef1adb50c53d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::DataExtractor::getCStr (uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
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

<p>Extract a C string from <em>*offset_ptr</em>.</p>


<p>Returns a pointer to a C String from the data at the offset pointed to by <em>offset_ptr</em>. A variable length NULL terminated C string will be extracted and the <em>offset_ptr</em> will be updated with the offset of the byte that follows the NULL terminator byte.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the C string value in the data. If the offset pointed to by <em>offset_ptr</em> is out of bounds, or if the offset plus the length of the C string is out of bounds, NULL will be returned.</p></dd>
</dl>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="#a3b587fe584a4e8b02c4ca0426be42918">getCStrRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#afb874a51b13c3cdfa8011bbf866c3658">dumpStringOffsetsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ae6bcf159d6ccb3adb4f7409e3adbbb37">llvm::DWARFFormValue::getAsCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#aca915d08912b7239d76d1044c7a8a073">llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getCStr() {#a98013dfe461d03c79996aa701959af99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::DataExtractor::getCStr (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a C string from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, a nullptr is returned.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="#a3b587fe584a4e8b02c4ca0426be42918">getCStrRef</a>.</p>

</div>
</div>

### getCStrRef() {#a3b587fe584a4e8b02c4ca0426be42918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DataExtractor::getCStrRef (uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a C string from <em>*offset_ptr</em>.</p>


<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the C String from the data at the offset pointed to by <em>offset_ptr</em>. A variable length NULL terminated C string will be extracted and the <em>offset_ptr</em> will be updated with the offset of the byte that follows the NULL terminator byte.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the C string value in the data. If the offset pointed to by <em>offset_ptr</em> is out of bounds, or if the offset plus the length of the C string is out of bounds, a default-initialized <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> will be returned.</p></dd>
</dl>


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba53a9e57a679708b2d8ff0ccd8ec96b18">llvm::illegal_byte_sequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#ac2a4c7453cbb40de6ef58bfe778554cb">isError</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a021fcf81d5e7d4534f0aaf4984381236">llvm::DWARFDebugPubTable::extract</a>, <a href="#a98013dfe461d03c79996aa701959af99">getCStr</a>, <a href="#a17638a9e9146a6f6feef1adb50c53d2b">getCStr</a>, <a href="#a8a63167c274c9f88ebe28d65a62b5109">getCStrRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>.</p>

</div>
</div>

### getCStrRef() {#a8a63167c274c9f88ebe28d65a62b5109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataExtractor::getCStrRef (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a C string (as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, a default-initialized <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> is returned.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a3b587fe584a4e8b02c4ca0426be42918">getCStrRef</a>.</p>

</div>
</div>

### getData() {#a882aa042b8549998c9ae43305a79d955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataExtractor::getData ()</td>
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

<p>Get the data pointed to by this extractor.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a7a9a9bc490d816bb7e08cb0eca3b54ae">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### getFixedLengthString() {#a01226a387955cebb0a2a163395a8a527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DataExtractor::getFixedLengthString (uint64_t * OffsetPtr, uint64_t Length, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TrimChars={"\0", 1})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a fixed length string from <em>*OffsetPtr</em> and consume <em>Length</em> bytes.</p>


<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the string from the data at the offset pointed to by <em>OffsetPtr</em>. A fixed length C string will be extracted and the <em>OffsetPtr</em> will be advanced by <em>Length</em> bytes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Length</td>
<td class="doxyParamItemDescription"><p>The length of the fixed length string to extract. If there are not enough bytes in the data to extract the full string, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TrimChars</td>
<td class="doxyParamItemDescription"><p>A set of characters to trim from the end of the string. Fixed length strings are commonly either NULL terminated by one or more zero bytes. Some clients have one or more spaces at the end of the string, but a good default is to trim the NULL characters.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the C string value in the data. If the offset pointed to by <em>OffsetPtr</em> is out of bounds, or if the offset plus the length of the C string is out of bounds, a default-initialized <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> will be returned.</p></dd>
</dl>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="#ade9e119455709c0d46a34464ebdbf179">getBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ab9990397f97b40d5d8564e000d00174a">llvm::StringRef::trim</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>.</p>

</div>
</div>

### getSigned() {#a5cc53bb122d7af1e40b77867d080114d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t DataExtractor::getSigned (uint64_t * offset_ptr, uint32_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract an signed integer of size <em>byte_size</em> from <em>*offset_ptr</em>.</p>


<p>Extract a single signed integer value (sign extending if required) and update the offset pointed to by <em>offset_ptr</em>. The size of the extracted integer is specified by the <em>byte_size</em> argument. <em>byte_size</em> should have a value greater than or equal to one and less than or equal to eight since the return value is 64 bits wide. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> <em>byte_size</em> values less than 1 or greater than 8 will result in nothing being extracted, and zero being returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] size</td>
<td class="doxyParamItemDescription"><p>The size in bytes of the integer to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The sign extended signed integer value that was extracted, or zero on failure.</p></dd>
</dl>


<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="#a98923ce73981e5171ef246bdcc6fde60">getU16</a>, <a href="#a0eb55ea3f585f9c8a2619fe7250e56f4">getU32</a>, <a href="#ac7c91465e0d075f5fc1bdc895c8a5f07">getU64</a>, <a href="#a45ee696c4102751e0194a0210c07dac0">getU8</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#ab0ceb7476c6b212e0f515e2a4cc9e551">llvm::DWARFDataExtractor::getEncodedPointer</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>.</p>

</div>
</div>

### getSLEB128() {#a88a902fb0c1d600e6b4fe880d770acdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t DataExtractor::getSLEB128 (uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a signed LEB128 value from <em>*offset_ptr</em>.</p>


<p>Extracts an signed LEB128 number from this object's data starting at the offset pointed to by <em>offset_ptr</em>. The offset pointed to by <em>offset_ptr</em> will be updated with the offset of the byte following the last extracted byte.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted signed integer value.</p></dd>
</dl>


<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#ab0ceb7476c6b212e0f515e2a4cc9e551">llvm::DWARFDataExtractor::getEncodedPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getSLEB128() {#a2642cbf3b909efa5f4c9033168236ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DataExtractor::getSLEB128 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract an signed LEB128 value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a2642cbf3b909efa5f4c9033168236ef2">getSLEB128</a>.</p>


<p>Referenced by <a href="#a2642cbf3b909efa5f4c9033168236ef2">getSLEB128</a>.</p>

</div>
</div>

### getU16() {#a98923ce73981e5171ef246bdcc6fde60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DataExtractor::getU16 (uint64_t * offset_ptr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a uint16_t value from <em>*offset_ptr</em>.</p>


<p>Extract a single uint16_t from the binary data at the offset pointed to by <em>offset_ptr</em>, and update the offset on success.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted uint16_t value.</p></dd>
</dl>


<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a021fcf81d5e7d4534f0aaf4984381236">llvm::DWARFDebugPubTable::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>, <a href="#a5cc53bb122d7af1e40b77867d080114d">getSigned</a>, <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a615332b0161a87347eea3360a5d51410">llvm::DWARFVerifier::handleDebugStrOffsets</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getU16() {#aa02ab439560d1a46c00cdcdf684d8bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DataExtractor::getU16 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a single uint16_t value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#aa02ab439560d1a46c00cdcdf684d8bb3">getU16</a>.</p>


<p>Referenced by <a href="#aa02ab439560d1a46c00cdcdf684d8bb3">getU16</a>.</p>

</div>
</div>

### getU16() {#a968738e950c817a5c90ebdb5adeaff08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t * DataExtractor::getU16 (uint64_t * offset_ptr, uint16_t * dst, uint32_t count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <em>count</em> uint16_t values from <em>*offset_ptr</em>.</p>


<p>Extract <em>count</em> uint16_t values from the binary data at the offset pointed to by <em>offset_ptr</em>, and advance the offset on success. The extracted values are copied into <em>dst</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] dst</td>
<td class="doxyParamItemDescription"><p>A buffer to copy <em>count</em> uint16_t values into. <em>dst</em> must be large enough to hold all requested data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] count</td>
<td class="doxyParamItemDescription"><p>The number of uint16_t values to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><em>dst</em> if all values were properly extracted and copied, NULL otherise.</p></dd>
</dl>


<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>.</p>

</div>
</div>

### getU24() {#ae76306ed98218d7cb53f099c42c0dbef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DataExtractor::getU24 (uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a 24-bit unsigned value from <em>*offset_ptr</em> and return it in a uint32_t.</p>


<p>Extract 3 bytes from the binary data at the offset pointed to by <em>offset_ptr</em>, construct a uint32_t from them and update the offset on success.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OffsetPtr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the 3 bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted 24-bit value represented in a uint32_t.</p></dd>
</dl>


<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/uint24/#a9e086b877c8e942124d446e97860ac27">llvm::Uint24::getAsUint32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>.</p>

</div>
</div>

### getU24() {#a80037e67b2902789a9092c21e141228d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DataExtractor::getU24 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a single 24-bit unsigned value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a80037e67b2902789a9092c21e141228d">getU24</a>.</p>


<p>Referenced by <a href="#a80037e67b2902789a9092c21e141228d">getU24</a>.</p>

</div>
</div>

### getU32() {#a0eb55ea3f585f9c8a2619fe7250e56f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DataExtractor::getU32 (uint64_t * offset_ptr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a uint32_t value from <em>*offset_ptr</em>.</p>


<p>Extract a single uint32_t from the binary data at the offset pointed to by <em>offset_ptr</em>, and update the offset on success.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted uint32_t value.</p></dd>
</dl>


<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a5ee76a16c0f9982c286540d84be2b819">debugStrOffsetsHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#aca915d08912b7239d76d1044c7a8a073">llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>, <a href="#a5cc53bb122d7af1e40b77867d080114d">getSigned</a>, <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getU32() {#a0779b218e615507e5be219472244ecf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DataExtractor::getU32 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a single uint32_t value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a0779b218e615507e5be219472244ecf9">getU32</a>.</p>


<p>Referenced by <a href="#a0779b218e615507e5be219472244ecf9">getU32</a>.</p>

</div>
</div>

### getU32() {#a2b99b78638b6b9f381619b62b32afef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t * DataExtractor::getU32 (uint64_t * offset_ptr, uint32_t * dst, uint32_t count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <em>count</em> uint32_t values from <em>*offset_ptr</em>.</p>


<p>Extract <em>count</em> uint32_t values from the binary data at the offset pointed to by <em>offset_ptr</em>, and advance the offset on success. The extracted values are copied into <em>dst</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] dst</td>
<td class="doxyParamItemDescription"><p>A buffer to copy <em>count</em> uint32_t values into. <em>dst</em> must be large enough to hold all requested data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] count</td>
<td class="doxyParamItemDescription"><p>The number of uint32_t values to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><em>dst</em> if all values were properly extracted and copied, NULL otherise.</p></dd>
</dl>


<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>.</p>

</div>
</div>

### getU64() {#ac7c91465e0d075f5fc1bdc895c8a5f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DataExtractor::getU64 (uint64_t * offset_ptr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a uint64_t value from <em>*offset_ptr</em>.</p>


<p>Extract a single uint64_t from the binary data at the offset pointed to by <em>offset_ptr</em>, and update the offset on success.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted uint64_t value.</p></dd>
</dl>


<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="#a5cc53bb122d7af1e40b77867d080114d">getSigned</a>, <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### getU64() {#ab2ffbd42e93818f0130cacaba3b5b431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::getU64 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a single uint64_t value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ab2ffbd42e93818f0130cacaba3b5b431">getU64</a>.</p>


<p>Referenced by <a href="#ab2ffbd42e93818f0130cacaba3b5b431">getU64</a>.</p>

</div>
</div>

### getU64() {#aac8a77c19e55900e7e234db43a439dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t * DataExtractor::getU64 (uint64_t * offset_ptr, uint64_t * dst, uint32_t count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <em>count</em> uint64_t values from <em>*offset_ptr</em>.</p>


<p>Extract <em>count</em> uint64_t values from the binary data at the offset pointed to by <em>offset_ptr</em>, and advance the offset on success. The extracted values are copied into <em>dst</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] dst</td>
<td class="doxyParamItemDescription"><p>A buffer to copy <em>count</em> uint64_t values into. <em>dst</em> must be large enough to hold all requested data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] count</td>
<td class="doxyParamItemDescription"><p>The number of uint64_t values to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><em>dst</em> if all values were properly extracted and copied, NULL otherise.</p></dd>
</dl>


<p>Declaration at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>.</p>

</div>
</div>

### getU8() {#a45ee696c4102751e0194a0210c07dac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t DataExtractor::getU8 (uint64_t * offset_ptr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a uint8_t value from <em>*offset_ptr</em>.</p>


<p>Extract a single uint8_t from the binary data at the offset pointed to by <em>offset_ptr</em>, and advance the offset on success.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted uint8_t value.</p></dd>
</dl>


<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a021fcf81d5e7d4534f0aaf4984381236">llvm::DWARFDebugPubTable::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a1dd96c0d1dd630ddd6a86a9914a58757">getCUAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>, <a href="#a5cc53bb122d7af1e40b77867d080114d">getSigned</a>, <a href="#a1c8968c4c97aefde2610f274d34d6c96">getU8</a>, <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a3c5f98145259c144797136c9e4d29af8">parseV5EntryFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/operation/#a776144ebd87427d17aaade268a4c1c6e">llvm::DWARFExpression::Operation::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getU8() {#acceb9d609466ce185f4d62cea308cf06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DataExtractor::getU8 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract a single uint8_t value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#acceb9d609466ce185f4d62cea308cf06">getU8</a>.</p>


<p>Referenced by <a href="#acceb9d609466ce185f4d62cea308cf06">getU8</a>.</p>

</div>
</div>

### getU8() {#a99714e6728aec45a983ebaa1e3a759b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * DataExtractor::getU8 (uint64_t * offset_ptr, uint8_t * dst, uint32_t count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <em>count</em> uint8_t values from <em>*offset_ptr</em>.</p>


<p>Extract <em>count</em> uint8_t values from the binary data at the offset pointed to by <em>offset_ptr</em>, and advance the offset on success. The extracted values are copied into <em>dst</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] dst</td>
<td class="doxyParamItemDescription"><p>A buffer to copy <em>count</em> uint8_t values into. <em>dst</em> must be large enough to hold all requested data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] count</td>
<td class="doxyParamItemDescription"><p>The number of uint8_t values to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><em>dst</em> if all values were properly extracted and copied, NULL otherise.</p></dd>
</dl>


<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>.</p>

</div>
</div>

### getU8() {#a410f6a91c0a8365d3be5010048789fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * DataExtractor::getU8 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint8_t * Dst, uint32_t Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <em>Count</em> uint8_t values from the location given by the cursor and store them into the destination buffer.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, a nullptr is returned and the destination buffer is left unchanged.</p>


<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>

</div>
</div>

### getU8() {#a1c8968c4c97aefde2610f274d34d6c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DataExtractor::getU8 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Dst, uint32_t Count)</td>
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

<p>Extract <em>Count</em> uint8_t values from the location given by the cursor and store them into the destination vector.</p>


<p>The vector is resized to fit the extracted data. In case of an extraction error, or if the cursor is already in an error state, the destination vector is left unchanged and cursor is placed into an error state.</p>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a45ee696c4102751e0194a0210c07dac0">getU8</a> and <a href="#ad7e3a2f9134fa59a38cc0a86acaaf351">isValidOffsetForDataOfSize</a>.</p>

</div>
</div>

### getULEB128() {#a6f2f68613d44758a66e49320fb075a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DataExtractor::getULEB128 (uint64_t * offset_ptr, <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a unsigned LEB128 value from <em>*offset_ptr</em>.</p>


<p>Extracts an unsigned LEB128 number from this object's data starting at the offset pointed to by <em>offset_ptr</em>. The offset pointed to by <em>offset_ptr</em> will be updated with the offset of the byte following the last extracted byte.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The extracted unsigned integer value.</p></dd>
</dl>


<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a8146aa10694a8fda28757fdd993823d9">llvm::DWARFDebugInfoEntry::extractFast</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a1dd96c0d1dd630ddd6a86a9914a58757">getCUAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#ab0ceb7476c6b212e0f515e2a4cc9e551">llvm::DWARFDataExtractor::getEncodedPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#a8475a510867f94e8f55f39ed0697d833">llvm::DWARFDebugNames::NameIndex::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a7e57705f8c616c73c69a74233ae964be">getIndexedString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a132fc2d4f9a680228706747b8608e269">parseV5DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a3c5f98145259c144797136c9e4d29af8">parseV5EntryFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ab6717ca91fe3922480a18f3e4250e611">llvm::object::MachOObjectFile::ReadULEB128s</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a4b10b1371b2d1f535ff65cf1aeed3158">llvm::DWARFFormValue::skipValue</a>.</p>

</div>
</div>

### getULEB128() {#a7f7cc5ebb4d6cf752224083a2eeea150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::getULEB128 (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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

<p>Extract an unsigned LEB128 value from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a7f7cc5ebb4d6cf752224083a2eeea150">getULEB128</a>.</p>


<p>Referenced by <a href="#a7f7cc5ebb4d6cf752224083a2eeea150">getULEB128</a>.</p>

</div>
</div>

### getUnsigned() {#a091e3b172c8f532c021b21c90fd3d461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DataExtractor::getUnsigned (uint64_t * offset_ptr, uint32_t byte_size, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract an unsigned integer of size <em>byte_size</em> from <em>*offset_ptr</em>.</p>


<p>Extract a single unsigned integer value and update the offset pointed to by <em>offset_ptr</em>. The size of the extracted integer is specified by the <em>byte_size</em> argument. <em>byte_size</em> should have a value greater than or equal to one and less than or equal to eight since the return value is 64 bits wide. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> <em>byte_size</em> values less than 1 or greater than 8 will result in nothing being extracted, and zero being returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] offset_ptr</td>
<td class="doxyParamItemDescription"><p>A pointer to an offset within the data that will be advanced by the appropriate number of bytes if the value is extracted correctly. If the offset is out of bounds or there are not enough bytes to extract this value, the offset will be left unmodified.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] byte_size</td>
<td class="doxyParamItemDescription"><p>The size in byte of the integer to extract.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Err</td>
<td class="doxyParamItemDescription"><p>A pointer to an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object. Upon return the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is set to indicate the result (success/failure) of the function. If the <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> object is already set when calling this function, no extraction is performed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The unsigned integer value that was extracted, or zero on failure.</p></dd>
</dl>


<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="#a98923ce73981e5171ef246bdcc6fde60">getU16</a>, <a href="#a0eb55ea3f585f9c8a2619fe7250e56f4">getU32</a>, <a href="#ac7c91465e0d075f5fc1bdc895c8a5f07">getU64</a>, <a href="#a45ee696c4102751e0194a0210c07dac0">getU8</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a021fcf81d5e7d4534f0aaf4984381236">llvm::DWARFDebugPubTable::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="#ade513e9d1a65b9918756e4d2af05228a">getAddress</a>, <a href="#a41d94746913373f82219a1d23e15ce31">getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#ab0ceb7476c6b212e0f515e2a4cc9e551">llvm::DWARFDataExtractor::getEncodedPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a814a7655e692e4f880b38eed143052fb">llvm::DWARFDataExtractor::getRelocatedValue</a> and <a href="#a7e826702732f1904f880287c57de1050">getUnsigned</a>.</p>

</div>
</div>

### getUnsigned() {#a7e826702732f1904f880287c57de1050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DataExtractor::getUnsigned (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint32_t Size)</td>
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

<p>Extract an unsigned integer of the given size from the location given by the cursor.</p>


<p>In case of an extraction error, or if the cursor is already in an error state, zero is returned.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a091e3b172c8f532c021b21c90fd3d461">getUnsigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isLittleEndian() {#ad9617bd42a629b75a6804af2cbcddddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataExtractor::isLittleEndian ()</td>
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

<p>Get the endianness for this extractor.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a7a9a9bc490d816bb7e08cb0eca3b54ae">llvm::DWARFDataExtractor::DWARFDataExtractor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a>.</p>

</div>
</div>

### isValidOffset() {#ad6c780b958be0ededd6a525ce67206bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataExtractor::isValidOffset (uint64_t offset)</td>
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

<p>Test the validity of <em>offset</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><b>true</b> if <em>offset</em> is a valid offset into the data in this object, <b>false</b> otherwise.</p></dd>
</dl>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="#a13f08bc0715c6ccbe15c82f2fc9e61ca">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aad9651c88d362ae11ea69508451b3ae6">dumpAddrSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a8146aa10694a8fda28757fdd993823d9">llvm::DWARFDebugInfoEntry::extractFast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#a8475a510867f94e8f55f39ed0697d833">llvm::DWARFDebugNames::NameIndex::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugline/#a966472d5c7f11678d9f2be08789bb4d3">llvm::DWARFDebugLine::getOrParseLineTable</a>, <a href="#ad7e3a2f9134fa59a38cc0a86acaaf351">isValidOffsetForDataOfSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>.</p>

</div>
</div>

### isValidOffsetForAddress() {#afdae60c28acfc86e2832ade183d3bc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataExtractor::isValidOffsetForAddress (uint64_t offset)</td>
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

<p>Test the availability of enough bytes of data for a pointer from <em>offset</em>.</p>


<p>The size of a pointer is <em><a href="#a727b157e8418a101ec69dcb2e9ceea39">getAddressSize()</a></em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><b>true</b> if <em>offset</em> is a valid offset and there are enough bytes for a pointer available at that offset, <b>false</b> otherwise.</p></dd>
</dl>


<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="#ad7e3a2f9134fa59a38cc0a86acaaf351">isValidOffsetForDataOfSize</a>.</p>

</div>
</div>

### isValidOffsetForDataOfSize() {#ad7e3a2f9134fa59a38cc0a86acaaf351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DataExtractor::isValidOffsetForDataOfSize (uint64_t offset, uint64_t length)</td>
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

<p>Test the availability of <em>length</em> bytes of data from <em>offset</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><b>true</b> if <em>offset</em> is a valid offset and there are <em>length</em> bytes available at that offset, <b>false</b> otherwise.</p></dd>
</dl>


<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="#ad6c780b958be0ededd6a525ce67206bb">isValidOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#acce40431959421046e6a001a951e8dd9">llvm::DWARFDebugNames::NameIndex::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#aca915d08912b7239d76d1044c7a8a073">llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents</a>, <a href="#a1c8968c4c97aefde2610f274d34d6c96">getU8</a>, <a href="#afdae60c28acfc86e2832ade183d3bc27">isValidOffsetForAddress</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a6b4f89ac434c992939934e78f19cd33e">anonymous{Trace.cpp}::loadFDRLog</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

### setAddressSize() {#ad1f5d1feac4b501f815939a0ca847d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DataExtractor::setAddressSize (uint8_t Size)</td>
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

<p>Set the address size for this extractor.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

### size() {#a13f08bc0715c6ccbe15c82f2fc9e61ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DataExtractor::size ()</td>
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

<p>Return the number of bytes in the underlying buffer.</p>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Referenced by <a href="#a80db7425f3e992ef519e25179f94fb56">DataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a9c4e8cde73237ab00ac91c380ff95f38">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="#a3ad190d933f6858fe3437ccf63bf8b65">eof</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="#ad6c780b958be0ededd6a525ce67206bb">isValidOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>.</p>

</div>
</div>

### skip() {#aa4c4043f99a1a5b283741ef4c7cf2464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DataExtractor::skip (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint64_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance the <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> position by the given number of bytes.</p>


<p>No-op if the cursor is in an error state.</p>


<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#ac2a4c7453cbb40de6ef58bfe778554cb">isError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a1ec298d8a742a9519e6dc0903f822f2b">llvm::AMDGPUDisassembler::decodeKernelDescriptorDirective</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getU() {#abc1752dc72b3507aa7a89716da308345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T DataExtractor::getU (uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>

</div>
</div>

### getUs() {#a7ed23b841961784abeec8f564ca66a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * DataExtractor::getUs (uint64_t * OffsetPtr, T * Dst, uint32_t Count, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>

</div>
</div>

### prepareRead() {#ad55fe6963d08fd0255315215d1d048ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DataExtractor::prepareRead (uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If it is possible to read <em>Size</em> bytes at offset <em>Offset</em>, returns <b>true</b>.</p>


<p>Otherwise, returns <b>false</b>. If <em>E</em> is not nullptr, also sets the error object to indicate an error.</p>


<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddressSize {#a89f7e64a18be7b976ba64d99addbfee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DataExtractor::AddressSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

### Data {#a4addaff512e4efcc676c1da4fc573ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DataExtractor::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

### IsLittleEndian {#a32b6ce5073dcad5adca0a3199328229a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DataExtractor::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getError() {#ad45d3690fa998e1a63931de09ff05bdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error &amp; llvm::DataExtractor::getError (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a1a6679ff65d9ecce4d14d11f9d1ce175">llvm::DWARFDataExtractor::getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a048e04c3ab40f799fd7e530b1be61f6a">llvm::DWARFDataExtractor::getRelocatedAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#afbe60ab4756377888e3bf33351d77c4a">llvm::DWARFDataExtractor::getRelocatedValue</a>.</p>

</div>
</div>

### getOffset() {#a2f74888abb46158e0f6ddec827c36922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t &amp; llvm::DataExtractor::getOffset (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a1a6679ff65d9ecce4d14d11f9d1ce175">llvm::DWARFDataExtractor::getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a048e04c3ab40f799fd7e530b1be61f6a">llvm::DWARFDataExtractor::getRelocatedAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#afbe60ab4756377888e3bf33351d77c4a">llvm::DWARFDataExtractor::getRelocatedValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">DataExtractor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp">DataExtractor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
