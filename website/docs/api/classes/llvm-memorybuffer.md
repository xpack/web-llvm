---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorybuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryBuffer` Class Reference

<p>This interface provides simple read-only access to a block of memory, and provides simple methods for reading files and standard input into a memory buffer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemoryBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer">SmallVectorMemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SmallVector-backed <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> instance. <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is an extension of <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, which allows copy-on-write access to the underlying contents. <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer">WriteThroughMemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is an extension of <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, which allows write access to the underlying contents and committing those changes to the original source. <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BufferKind { <a href="#a13d3f2713d567f925cb4efecf94d2101">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of memory backing used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a13d3f2713d567f925cb4efecf94d2101">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437989b9380e9a267f41c9609d715171">MemoryBuffer</a> (const MemoryBuffer &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16af83479e1c1ae07476634871e2e81">MemoryBuffer</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ee6c2cc704397982f60f930a60089e">~MemoryBuffer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9a6ed12ab134a66c393ec33e658ea5">operator=</a> (const MemoryBuffer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1972b9a0324e0311ad641eac2de2b7f">getBufferStart</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4604d3bedbb15e6c516f9357d3b773e">getBufferEnd</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea075bd68f15b57e95f0771b8ba0bca">getBufferSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d9843621ff4677c0b9087277dc4bd0">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2037f11968aa30bfda0b4de9f335624d">getBufferIdentifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an identifier for this buffer, typically the filename it was read from. <a href="#a2037f11968aa30bfda0b4de9f335624d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84540ead6f0846d050a11c007f892f00">dontNeedIfMmap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For read-only MemoryBuffer_MMap, mark the buffer as unused in the near future and the kernel can free resources associated with it. <a href="#a84540ead6f0846d050a11c007f892f00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a13d3f2713d567f925cb4efecf94d2101">BufferKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e088028b10d6efaadc983482a6fb7d">getBufferKind</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return information on the memory mechanism used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a45e088028b10d6efaadc983482a6fb7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9181a190ad7bd1e7bfb67f90c3e4d4">getMemBufferRef</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bdc0595208acb83e6b715bbed8e331">init</a> (const char *BufStart, const char *BufEnd, bool RequiresNullTerminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>init - Initialize this <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a reference to externally allocated memory, memory that we know is already null terminated. <a href="#a57bdc0595208acb83e6b715bbed8e331">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9034848575a96838e78a98c4fc24a394">BufferStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0aec25b3ab3832d729954dc94faaa42">BufferEnd</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa98611beefe78f907beeee7305cc8174">getFile</a> (const Twine &amp;Filename, bool IsText=false, bool RequiresNullTerminator=true, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, returning a new <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> if successful, otherwise returning null. <a href="#aa98611beefe78f907beeee7305cc8174">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b193577aa67b1fac72cdbb5343241a">getFileAsStream</a> (const Twine &amp;Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read all of the specified file into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a stream (i.e. <a href="#a76b193577aa67b1fac72cdbb5343241a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4432e24dbd29bafd528e623c04c62395">getOpenFileSlice</a> (sys::fs::file_t FD, const Twine &amp;Filename, uint64_t MapSize, int64_t Offset, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an already-open file descriptor, map some slice of it into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a4432e24dbd29bafd528e623c04c62395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0163ef693f4fd640ec72a5fe74e5852c">getOpenFile</a> (sys::fs::file_t FD, const Twine &amp;Filename, uint64_t FileSize, bool RequiresNullTerminator=true, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an already-open file descriptor, read the file and return a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a0163ef693f4fd640ec72a5fe74e5852c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f68098734d6d3b451aacf5b38a67131">getMemBuffer</a> (StringRef InputData, StringRef BufferName="", bool RequiresNullTerminator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a0f68098734d6d3b451aacf5b38a67131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1821192144d28e409d3eb945b5f19bb0">getMemBuffer</a> (MemoryBufferRef Ref, bool RequiresNullTerminator=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d2c9ba9019e6e41605c60acd06bd09">getMemBufferCopy</a> (StringRef InputData, const Twine &amp;BufferName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, copying the contents and taking ownership of it. <a href="#a32d2c9ba9019e6e41605c60acd06bd09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56e946cf4266646c30b0898033b88bc">getSTDIN</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read all of stdin into a file buffer, and return it. <a href="#ae56e946cf4266646c30b0898033b88bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c54e2428ad0163441789c281ca42ee4">getFileOrSTDIN</a> (const Twine &amp;Filename, bool IsText=false, bool RequiresNullTerminator=true, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, or open stdin if the Filename is "-". <a href="#a9c54e2428ad0163441789c281ca42ee4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa519672f542c6c93e950a9a9a6b14817">getFileSlice</a> (const Twine &amp;Filename, uint64_t MapSize, uint64_t Offset, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a subrange of the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#aa519672f542c6c93e950a9a9a6b14817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This interface provides simple read-only access to a block of memory, and provides simple methods for reading files and standard input into a memory buffer.</p>


<p>In addition to basic access to the characters in the file, this interface guarantees you can read one character past the end of the file, and that this character will read as '\0'.</p>


<p>The '\0' guarantee is needed to support an optimization – it's intended to be more efficient for clients which are reading all the data to stop reading when they encounter a '\0' than to continually check the file position to see if it has reached the end of the file.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BufferKind {#a13d3f2713d567f925cb4efecf94d2101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MemoryBuffer::BufferKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of memory backing used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemoryBuffer_Malloc<a id="a13d3f2713d567f925cb4efecf94d2101a04490e92687f2131e16c8d340ce01930"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemoryBuffer_MMap<a id="a13d3f2713d567f925cb4efecf94d2101a0826d9dda95a52edd55f495d5f638771"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryBuffer() {#a437989b9380e9a267f41c9609d715171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryBuffer::MemoryBuffer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp;)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Reference <a href="#ac16af83479e1c1ae07476634871e2e81">MemoryBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MemoryBuffer() {#ac16af83479e1c1ae07476634871e2e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryBuffer::MemoryBuffer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Referenced by <a href="#a437989b9380e9a267f41c9609d715171">MemoryBuffer</a> and <a href="#a9d9a6ed12ab134a66c393ec33e658ea5">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MemoryBuffer() {#a98ee6c2cc704397982f60f930a60089e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBuffer::~MemoryBuffer ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9d9a6ed12ab134a66c393ec33e658ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBuffer &amp; llvm::MemoryBuffer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp;)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Reference <a href="#ac16af83479e1c1ae07476634871e2e81">MemoryBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dontNeedIfMmap() {#a84540ead6f0846d050a11c007f892f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MemoryBuffer::dontNeedIfMmap ()</td>
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

<p>For read-only MemoryBuffer_MMap, mark the buffer as unused in the near future and the kernel can free resources associated with it.</p>


<p>Further access is supported but may be expensive. This calls madvise(MADV_DONTNEED) on read-only file mappings on *NIX systems. This function should not be called on a writable buffer.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

### getBuffer() {#a69d9843621ff4677c0b9087277dc4bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBuffer::getBuffer ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Reference <a href="#a2ea075bd68f15b57e95f0771b8ba0bca">getBufferSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryfileadaptor/#a1266e809afb8ce2716f84fc836dad25e">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryFileAdaptor::getBuffer</a>, <a href="#a8f9181a190ad7bd1e7bfb67f90c3e4d4">getMemBufferRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#aeedad20be775a7811deb410cb58936a0">GetOrCreateOffsetCache</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#a3312e664f5df1acd8f78ea8b824e7b5d">llvm::memprof::YAMLMemProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a0199559e6f0464acf4c2c30bcb041a03">llvm::TextCodeGenDataReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4571f3c6ad2b03f15e98bd2ba964888e">llvm::WritableMemoryBuffer::WritableMemoryBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a06117131e4bf6b50632601c865e124d6">llvm::WriteThroughMemoryBuffer::WriteThroughMemoryBuffer</a>.</p>

</div>
</div>

### getBufferEnd() {#ae4604d3bedbb15e6c516f9357d3b773e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBuffer::getBufferEnd ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerimpl/#a03459afe90e9865de42de9912ec0c972">llvm::RuntimeDyldCheckerImpl::checkAllRulesInBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a82b60c8deaa06915cacf9e571cb6f894">llvm::memprof::anonymous{MemProfReader.cpp}::checkBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#ae1220c05a9c901648d43e36ee6df59f6">llvm::WritableMemoryBuffer::getBufferEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a5de3e1aa047d79f056334d40cd32e287">llvm::WriteThroughMemoryBuffer::getBufferEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage/#af03b9404e0ae4bd9abacbd8cf9221240">llvm::CodeGenCoverage::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#aa883a589f91024d0a09d1b3c1821ec85">readBinaryIdsInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4571f3c6ad2b03f15e98bd2ba964888e">llvm::WritableMemoryBuffer::WritableMemoryBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a06117131e4bf6b50632601c865e124d6">llvm::WriteThroughMemoryBuffer::WriteThroughMemoryBuffer</a>.</p>

</div>
</div>

### getBufferIdentifier() {#a2037f11968aa30bfda0b4de9f335624d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::MemoryBuffer::getBufferIdentifier ()</td>
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

<p>Return an identifier for this buffer, typically the filename it was read from.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryfileadaptor/#a1266e809afb8ce2716f84fc836dad25e">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryFileAdaptor::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile/#a60467929ca4e3dfc265b6c462adbd83c">llvm::pdb::InputFile::getFilePath</a>, <a href="#a8f9181a190ad7bd1e7bfb67f90c3e4d4">getMemBufferRef</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### getBufferKind() {#a45e088028b10d6efaadc983482a6fb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual BufferKind llvm::MemoryBuffer::getBufferKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return information on the memory mechanism used to support the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

### getBufferSize() {#a2ea075bd68f15b57e95f0771b8ba0bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MemoryBuffer::getBufferSize ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a82b60c8deaa06915cacf9e571cb6f894">llvm::memprof::anonymous{MemProfReader.cpp}::checkBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="#a69d9843621ff4677c0b9087277dc4bd0">getBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#aeedad20be775a7811deb410cb58936a0">GetOrCreateOffsetCache</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#ab6239b296c0498d12a965b70fba539d7">llvm::memprof::RawMemProfReader::hasFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#a54ea33c903b163ee020c34e36d6849c9">llvm::TextInstrProfReader::hasFormat</a>.</p>

</div>
</div>

### getBufferStart() {#af1972b9a0324e0311ad641eac2de2b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBuffer::getBufferStart ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerimpl/#a03459afe90e9865de42de9912ec0c972">llvm::RuntimeDyldCheckerImpl::checkAllRulesInBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a82b60c8deaa06915cacf9e571cb6f894">llvm::memprof::anonymous{MemProfReader.cpp}::checkBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#aa7def6ecf63f529b0f7b9009a8140211">llvm::WritableMemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a9a2e10f095daee2823167f508d225430">llvm::WriteThroughMemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#ab6239b296c0498d12a965b70fba539d7">llvm::memprof::RawMemProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#a54ea33c903b163ee020c34e36d6849c9">llvm::TextInstrProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage/#af03b9404e0ae4bd9abacbd8cf9221240">llvm::CodeGenCoverage::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#a91e332bfcd4030aa1b14feb8792ff8f3">llvm::memprof::RawMemProfReader::peekBuildIds</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4571f3c6ad2b03f15e98bd2ba964888e">llvm::WritableMemoryBuffer::WritableMemoryBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a06117131e4bf6b50632601c865e124d6">llvm::WriteThroughMemoryBuffer::WriteThroughMemoryBuffer</a>.</p>

</div>
</div>

### getMemBufferRef() {#a8f9181a190ad7bd1e7bfb67f90c3e4d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBufferRef MemoryBuffer::getMemBufferRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a69d9843621ff4677c0b9087277dc4bd0">getBuffer</a> and <a href="#a2037f11968aa30bfda0b4de9f335624d">getBufferIdentifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a969833caa131b8a26c7b12bf917294a7">llvm::LTOModule::getProducerString</a> and <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aa9588be24002d2f7603334d8dd1846e7">llvm::LTOModule::isBitcodeForTarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### init() {#a57bdc0595208acb83e6b715bbed8e331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryBuffer::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BufStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BufEnd, bool RequiresNullTerminator)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>init - Initialize this <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a reference to externally allocated memory, memory that we know is already null terminated.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem/#ad093e9036111f8dae17691a756eae14f">anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::MemoryBufferMem</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile/#a2c9ab83ebcf60eb23389620b47c6e9b6">anonymous{MemoryBuffer.cpp}::MemoryBufferMMapFile&lt; MB &gt;::MemoryBufferMMapFile</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectormemorybuffer/#a446025d445ca22ed2295d2bc8f9ce590">llvm::SmallVectorMemoryBuffer::SmallVectorMemoryBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BufferEnd {#ac0aec25b3ab3832d729954dc94faaa42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MemoryBuffer::BufferEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

### BufferStart {#a9034848575a96838e78a98c4fc24a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MemoryBuffer::BufferStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFile() {#aa98611beefe78f907beeee7305cc8174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, bool IsText=false, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, returning a new <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> if successful, otherwise returning null.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsText</td>
<td class="doxyParamItemDescription"><p>Set to true to indicate that the file should be read in text mode.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsVolatile</td>
<td class="doxyParamItemDescription"><p>Set to true to indicate that the contents of the file can change outside the user's control, e.g. when libclang tries to parse while the user is editing/updating the file or if the file is on an NFS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>Set to indicate that the buffer should be aligned to at least the specified alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1fbf6763e62eb4e5268f421eee37d6b1">llvm::MachO::DylibReader::accumulateSourceLocFromDSYM</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a933d031a629f7261df21829fbea78f94">llvm::LTOCodeGenerator::compileOptimized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#aace1e8dbb3956766bdd52e5cac572da2">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a18b55d565c6a0be0a063486e7c905cef">llvm::LTOModule::createFromFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae465be28151991b2345f467899ddb5e5">llvm::remarks::createYAMLParserFromMeta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a23cbef0272f92b38f3f6654ce8af1cfb">anonymous{DlltoolDriver.cpp}::doIdentify</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3a01ed22efa91390e377a44b45087d8">llvm::doSystemDiff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79c3f6c8d0e321d8b23f365e485bfde7">llvm::findVCToolChainViaSetupConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ad3a7b88fce11b12853e7b60a06a033ec">llvm::InstrProfCorrelator::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac72192305c89532b4469f8533b6ecf5b">llvm::codegen::getBBSectionsMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a03bfd76bddfe1a42326e93dc3c131c8c">llvm::object::Archive::Child::getBuffer</a>, <a href="#a9c54e2428ad0163441789c281ca42ee4">getFileOrSTDIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae37fdf2c48e64e5ec89afa5a44774e99">llvm::getHeaders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/unittest/#aa3aa8b23b1c244615ed10c125922fc05">llvm::unittest::getInputFileDirectory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f74016c4c5e7cdf1748f08054456621">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#af8c1c55aabd3c2fe773936a5aeec05c8">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga882a7aff0ee42d8def45505c07cb1588">LLVMCreateMemoryBufferWithContentsOfFile</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac6293b7ea84a4deac85481dd10dad437">llvm::OpenMPIRBuilder::loadOffloadInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/callsiteinfoloader/#af96a5f4033bb285a8570b073578aceb1">llvm::gsym::CallSiteInfoLoader::loadYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#abfc69efe5e1b61e475c294e22e3601d5">llvm::MemProfContextDisambiguation::MemProfContextDisambiguation</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile/#a7b4528e86b5fa28d9fd927aa31a8fcd2">llvm::pdb::InputFile::open</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a63c23d0d95493a7fea1b8ff024cef529">anonymous{DlltoolDriver.cpp}::openFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#aac4d1354e91eabfb6600271e40bdf05a">openFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a0c8517e1b412dcd4f30cdce1c9541cc9">llvm::SourceMgr::OpenIncludeFile</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritemapparser/#a73f3ae9cac7a4557bd5c1e311548cd26">llvm::SymbolRewriter::RewriteMapParser::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#aff85944087fc349e227e8b737179cb3e">parseCHRFilterFiles</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a0cbc02f8988e793203b0a4f7e75587c0">llvm::CtxProfAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a2fee796681f58a9d96414dcaac5bb642">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::runForTesting</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#adf63c9ebc3de0773617afcdbd321f43b">anonymous{WholeProgramDevirt.cpp}::DevirtModule::runForTesting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73f3f480c52fd84aac6182d798979181">llvm::runFuzzerOnInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a101c2836638ffc1c34e2e502ad68d0da">llvm::ifs::writeELFBinaryToFile</a>.</p>

</div>
</div>

### getFileAsStream() {#a76b193577aa67b1fac72cdbb5343241a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFileAsStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename)</td>
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

<p>Read all of the specified file into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a stream (i.e.</p>


<p>until EOF reached). This is useful for special files that look like a regular file but have 0 size (e.g. /proc/cpuinfo on Linux).</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a43548658b3d92c080577422f81f38038">llvm::sys::fs::closeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#aad17f4118ff721e4675c06f38373a7d1">getMemoryBufferForStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ae025e411759250214ffc53ab8d8a5e1d">llvm::sys::fs::openNativeFileForRead</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/host-cpp/#a03ee6e57339003249d55cef525fc8684">getProcCpuinfoContent</a>.</p>

</div>
</div>

### getFileOrSTDIN() {#a9c54e2428ad0163441789c281ca42ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFileOrSTDIN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, bool IsText=false, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, or open stdin if the Filename is "-".</p>

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="#aa98611beefe78f907beeee7305cc8174">getFile</a> and <a href="#ae56e946cf4266646c30b0898033b88bc">getSTDIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#ade75bef9f219b31ef89e452d482e59a7">llvm::symbolize::anonymous{Symbolize.cpp}::checkFileCRC</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#a529ab1228d3ec2e3eb5e89d8871751ba">llvm::memprof::RawMemProfReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#a77027f7da4a6c0240777e8fe6aa4912d">llvm::memprof::YAMLMemProfReader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a12fb918c70f7885e7a8286a74548d860">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9c588cc76fd836085e21c0aa3ca50">llvm::createMIRParserFromFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac226baa3ffd0f255a8d2b6d978b81b2">llvm::getLazyIRFileModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7fed2696a3bda04b9f93d8b986758b3">llvm::getModuleSummaryIndexForFile</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#afaa5bd7225c533cda8178eb88b6b25fc">llvm::memprof::RawMemProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#a61cde3150c070e36e72b24eac157b5ad">llvm::memprof::YAMLMemProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/lineconsumer/#a48d140d0cd7e4ecf51e1192d6dc9910d">anonymous{GCOV.cpp}::LineConsumer::LineConsumer</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a3cc6f8b4a312834f3683fa1a90bda0ed">llvm::gsym::GsymReader::openFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a2a0bea39c1731326a7e3504cba4da">llvm::parseAssemblyFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#aff85bfef450fa1ae5ee06c97367f94e4">parseAssemblyFileWithIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f23ddc70c8c903ce27bcef2e37f9d59">llvm::parseIRFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65a056610f168d74a85291f1c00c6d7a">llvm::parseSummaryIndexAssemblyFile</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a2c5f266941c1a559e1e8152c4f274307">llvm::ReplayInlineAdvisor::ReplayInlineAdvisor</a>, <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#ad69a1886cef737f69d223f2ffa24d35f">searchForObj</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### getFileSlice() {#aa519672f542c6c93e950a9a9a6b14817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFileSlice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t MapSize, uint64_t Offset, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Map a subrange of the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getMemBuffer() {#a0f68098734d6d3b451aacf5b38a67131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BufferName="", bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<p>Note that InputData must be null terminated if RequiresNullTerminator is true.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#aafccb9d37b4780a41412379355a4cf41">llvm::vfs::InMemoryFileSystem::addFileNoOwn</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a413fb17148951e24c4da93ab845f78b3">llvm::yaml::Output::blockScalarString</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a5f897499fea3f1a9fbb5c0fb2a363a20">llvm::GlobalMergeFunc::emitFunctionMap</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a7fe992f3a0f55c247f1f27cb09755ab5">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedHashTree</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#aa2f8f902ed35880d4ccb900b4ddbe2c1">anonymous{OffloadBinary.cpp}::extractFromArchive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a0f076ea04eda5249d0527c704881cdf1">anonymous{OffloadBinary.cpp}::extractFromBitcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryfileadaptor/#a1266e809afb8ce2716f84fc836dad25e">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryFileAdaptor::getBuffer</a>, <a href="#a1821192144d28e409d3eb945b5f19bb0">getMemBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gaeff7af5e130db7b11a27ed233f57d5c6">LLVMBinaryCopyMemoryBuffer</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga7c3477be54bb97a189b19ccb5e5c06fd">LLVMCreateMemoryBufferWithMemoryRange</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a16a84f60ff615b07935df943c5f84a5e">llvm::orc::StaticLibraryDefinitionGenerator::loadAllObjectFileMembers</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a71a8c6078191280b00feef9864b58338">loadBinaryFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aedbd5b8bb99f2c1816738f4687a3b43a">llvm::cgdata::loadModuleForTwoRounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7851b0072b1b5a3330cda84355b476d3">loadTestingFormat</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a506f8e95d7b36007cf41322e49e3668c">llvm::LTOModule::makeBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/forceloadmachoarchivemembers/#aafbc2404a509204e5983e140d1038581">llvm::orc::ForceLoadMachOArchiveMembers::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a982f596dc670886cba9172ea00cb7a48">parseAssemblyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf2c472d771169c6100c6302079309da">llvm::parseConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a693d5398216b0ca25097c2bde8fe6284">llvm::parseDIExpressionBodyAtBeginning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39aacf94d621d7c81b663f33629fc839">llvm::parseModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a3f2868a82e652c99a57c4dd99683af87">parseSummaryIndexAssemblyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add17c7296500b889d12eb44d547a59ba">llvm::parseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35d32e57764638fe887f59392490e49c">llvm::parseTypeAtBeginning</a>, <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0cd59afcda8972c7ffd9254da83b7d70">llvm::orc::COFFPlatform::setupJITDylib</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a553c068fc6fde1b82ee28bbc7bd11a8f">llvm::orc::StaticLibraryDefinitionGenerator::tryToGenerate</a>.</p>

</div>
</div>

### getMemBuffer() {#a1821192144d28e409d3eb945b5f19bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBuffer (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Ref, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="#a0f68098734d6d3b451aacf5b38a67131">getMemBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getMemBufferCopy() {#a32d2c9ba9019e6e41605c60acd06bd09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBufferCopy (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName="")</td>
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

<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, copying the contents and taking ownership of it.</p>


<p>InputData does not have to be null terminated.</p>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a8da8a8e7960a91583ad18b42ecbbadeb">getMemBufferCopyImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile/#a9b4886b96406a196d56ea326687ba908">llvm::object::OffloadFile::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#ad2040abae29e3f6423e313d74955aa1c">llvm::gsym::GsymReader::copyBuffer</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a4c89c8ae8b758aaf88cb3ddcb0a25c20">anonymous{RuntimeDyldELF.cpp}::createELFDebugObject</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a1bf0b70372e2ca4b1e9540e9c4f8aa41">emitDebugSectionImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#aa2f8f902ed35880d4ccb900b4ddbe2c1">anonymous{OffloadBinary.cpp}::extractFromArchive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a42dbc5cc7c04f8d8738edf9699d75654">llvm::objcopy::wasm::handleArgs</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#gae4474b2308abb1fedcb326e253b7fd41">LLVMCreateMemoryBufferWithMemoryRangeCopy</a>, <a href="/web-llvm/docs/api/groups/llvmcbitwriter/#ga43cccd6ab4fe5c042fc59d972430c97f">LLVMWriteBitcodeToMemoryBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a71a8c6078191280b00feef9864b58338">loadBinaryFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#acbb5997231c5c31ee92f0aec0807dbfb">llvm::InstrProfWriter::writeBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a960217c66ca1fa6c96ec78eba269b580">llvm::yaml::yaml2offload</a>.</p>

</div>
</div>

### getOpenFile() {#a0163ef693f4fd640ec72a5fe74e5852c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getOpenFile (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t FileSize, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Given an already-open file descriptor, read the file and return a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsVolatile</td>
<td class="doxyParamItemDescription"><p>Set to true to indicate that the contents of the file can change outside the user's control, e.g. when libclang tries to parse while the user is editing/updating the file or if the file is on an NFS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>Set to indicate that the buffer should be aligned to at least the specified alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/realfile/#ac5d5622ef3be1339d2984f1c7a752ab3">anonymous{VirtualFileSystem.cpp}::RealFile::getBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aabc893bb91367b69e0edf27249081a78">llvm::NewArchiveMember::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a325b7b8ec75f271d91355d4216b6c4">llvm::orc::loadLinkableFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae6cbf068071c82d07501b056bf146c3f">llvm::orc::loadMachORelocatableObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7c58f347a240684b93eb7ee8bfd6824">llvm::streamFile</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#a024b9505d8018b5086d36b13c3af8232">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::tryLoadingBuffer</a>.</p>

</div>
</div>

### getOpenFileSlice() {#a4432e24dbd29bafd528e623c04c62395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getOpenFileSlice (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t MapSize, int64_t Offset, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Given an already-open file descriptor, map some slice of it into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<p>The slice is specified by an <span class="doxyComputerOutput">Offset</span> and <span class="doxyComputerOutput">MapSize</span>. Since this is in the middle of a file, the buffer is not null terminated.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a8c515c45d2e7357a98e076263ff9ee68">llvm::LTOModule::createFromOpenFileSlice</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a23f400453ec5ee74f48de908ba27bc6c">llvm::orc::loadLinkableSliceFromMachOUniversalBinary</a>.</p>

</div>
</div>

### getSTDIN() {#ae56e946cf4266646c30b0898033b88bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getSTDIN ()</td>
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

<p>Read all of stdin into a file buffer, and return it.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a1b6956e6c738949193efee28bffe29f5">llvm::sys::ChangeStdinMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#aad17f4118ff721e4675c06f38373a7d1">getMemoryBufferForStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#affa4b5f37e8e5689ee7857b1e6d76bf7">llvm::sys::fs::getStdinHandle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a>.</p>


<p>Referenced by <a href="#a9c54e2428ad0163441789c281ca42ee4">getFileOrSTDIN</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga471f90956bfd49f4a5ecb522cfd6c1f5">LLVMCreateMemoryBufferWithSTDIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c339cfce77238670cd7657a636f4303">llvm::setupMemoryBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#a0810556060b6af1743ccf23023fdae47">setupMemoryBuffer</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a0c882627d1252f1c30eb5bd284ed093b">setupMemoryBuffer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
