---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executorsymboldef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExecutorSymbolDef` Class Reference

<p>Represents a defining location for a JIT symbol. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutorSymbolDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">llvm/ExecutionEngine/Orc/Shared/ExecutorSymbolDef.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15111e09fbfcac9f7256a1360bee4bbd">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288b02b080d8f97174495df5dfe7970c">operator!=</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d319565f4d469865bf57a1384e57235">ExecutorSymbolDef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5faaa48261fca6ca7b6723a8665d1783">ExecutorSymbolDef</a> (ExecutorAddr Addr, JITSymbolFlags Flags)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39c0c4e92038941ee7821130b81776d5">toPtr</a> (WrapFn &amp;&amp;Wrap=WrapFn()) const -&gt; std::enable_if_t&lt; std::is_pointer&lt; T &gt;::value, T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> to a pointer of the given type. <a href="#a39c0c4e92038941ee7821130b81776d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename WrapFn = ExecutorAddr::defaultWrap&lt;T&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe353cb36461f2f4475fa41d3cbcdc9c">toPtr</a> (WrapFn &amp;&amp;Wrap=WrapFn()) const -&gt; std::enable_if_t&lt; std::is_function&lt; T &gt;::value, T * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> to a pointer of the given function type. <a href="#afe353cb36461f2f4475fa41d3cbcdc9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37d28cfc286061fc4faddf19b517e99">getAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fb83276d38c4f5d825aae80e8a76e8">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff440f2e311ac4bbec9bf0be11dad50">setFlags</a> (JITSymbolFlags Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6699306cd9b035e346924246ecb7977">Addr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89433608c293001a0c39ff943bbaf6a6">Flags</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4027523e233ec73fad998066e26ffc71">fromPtr</a> (T *Ptr, JITSymbolFlags BaseFlags=JITSymbolFlags(), UnwrapFn &amp;&amp;Unwrap=UnwrapFn())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> from the given pointer. <a href="#a4027523e233ec73fad998066e26ffc71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a defining location for a JIT symbol.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator!= {#a288b02b080d8f97174495df5dfe7970c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &amp; RHS</td>
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


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>References <a href="#a8d319565f4d469865bf57a1384e57235">ExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator== {#a15111e09fbfcac9f7256a1360bee4bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &amp; RHS</td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>References <a href="#a8d319565f4d469865bf57a1384e57235">ExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExecutorSymbolDef() {#a8d319565f4d469865bf57a1384e57235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorSymbolDef::ExecutorSymbolDef ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>Referenced by <a href="#a4027523e233ec73fad998066e26ffc71">fromPtr</a>, <a href="#a288b02b080d8f97174495df5dfe7970c">operator!=</a> and <a href="#a15111e09fbfcac9f7256a1360bee4bbd">operator==</a>.</p>

</div>
</div>

### ExecutorSymbolDef() {#a5faaa48261fca6ca7b6723a8665d1783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorSymbolDef::ExecutorSymbolDef (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddress() {#af37d28cfc286061fc4faddf19b517e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ExecutorAddr &amp; llvm::orc::ExecutorSymbolDef::getAddress ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#a25ef4ea37fd470785124fe531d34dd08">LLVMOrcLazyCallThroughManagerRef::fromExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aebb757ece6adac588a966ea1e6b12dbb">llvm::orc::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c/#a827a63d495b35011f21af9ed188edc59">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorSymbolDef, ExecutorSymbolDef &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c/#a23051aa08752f1b73f87703440a892b5">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorSymbolDef, ExecutorSymbolDef &gt;::size</a>.</p>

</div>
</div>

### getFlags() {#ad8fb83276d38c4f5d825aae80e8a76e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JITSymbolFlags &amp; llvm::orc::ExecutorSymbolDef::getFlags ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#a25ef4ea37fd470785124fe531d34dd08">LLVMOrcLazyCallThroughManagerRef::fromExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery/#a840fe6c687a1b9b1597ba8f5e5bf6e36">llvm::orc::AsynchronousSymbolQuery::notifySymbolMetRequiredState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aebb757ece6adac588a966ea1e6b12dbb">llvm::orc::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c/#a827a63d495b35011f21af9ed188edc59">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorSymbolDef, ExecutorSymbolDef &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c/#a23051aa08752f1b73f87703440a892b5">llvm::orc::shared::SPSSerializationTraits&lt; SPSExecutorSymbolDef, ExecutorSymbolDef &gt;::size</a>.</p>

</div>
</div>

### setFlags() {#a0ff440f2e311ac4bbec9bf0be11dad50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ExecutorSymbolDef::setFlags (<a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

### toPtr() {#a39c0c4e92038941ee7821130b81776d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename WrapFn = ExecutorAddr::defaultWrap&lt;std::remove_pointer_t&lt;T&gt;&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_pointer&lt; T &gt;::value, T &gt; llvm::orc::ExecutorSymbolDef::toPtr (WrapFn &amp;&amp; Wrap=WrapFn())</td>
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

<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> to a pointer of the given type.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### toPtr() {#afe353cb36461f2f4475fa41d3cbcdc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename WrapFn = ExecutorAddr::defaultWrap&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_function&lt; T &gt;::value, T * &gt; llvm::orc::ExecutorSymbolDef::toPtr (WrapFn &amp;&amp; Wrap=WrapFn())</td>
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

<p>Cast this <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> to a pointer of the given function type.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Addr {#ad6699306cd9b035e346924246ecb7977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::ExecutorSymbolDef::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

### Flags {#a89433608c293001a0c39ff943bbaf6a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::orc::ExecutorSymbolDef::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromPtr() {#a4027523e233ec73fad998066e26ffc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename UnwrapFn = ExecutorAddr::defaultUnwrap&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorSymbolDef llvm::orc::ExecutorSymbolDef::fromPtr (T * Ptr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> BaseFlags=<a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a>(), UnwrapFn &amp;&amp; Unwrap=UnwrapFn())</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> from the given pointer.</p>


<p>Warning: This should only be used when JITing in-process.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">llvm::JITSymbolFlags::Callable</a>, <a href="#a8d319565f4d469865bf57a1384e57235">ExecutorSymbolDef</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
