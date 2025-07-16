---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofcorrelatorimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrProfCorrelatorImpl` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> with a template pointer type so that the ProfileData vector can be materialized. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class IntPtrT&gt;
class llvm::InstrProfCorrelatorImpl&lt;IntPtrT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">llvm/ProfileData/InstrProfCorrelator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> - A base class used to create raw instrumentation data to their functions. <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator">BinaryInstrProfCorrelator&lt;IntPtrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator">BinaryInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes an object file as input to correlate profiles. <a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator">DwarfInstrProfCorrelator&lt;IntPtrT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator">DwarfInstrProfCorrelator</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> that takes DWARF debug info as input to correlate profiles. <a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9110dae8cefc94bca7e5f15b038b2d6a">InstrProfCorrelatorImpl</a> (std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afcaf567d257fbc2765841a650dfbea39">InstrProfCorrelatorImpl</a> (std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adf8cb0ea37a236a4e14082085f9871af">InstrProfCorrelatorImpl</a> (std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a029f808eb3fc90fb806ca0f966499fbc">InstrProfCorrelatorImpl</a> (InstrProfCorrelatorKind Kind, std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4e004aaac42330a5dd2883204988cf5">getDataPointer</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rawinstrprof/profiledata">RawInstrProf::ProfileData</a>&lt; IntPtrT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the underlying ProfileData vector that this class constructs. <a href="#aa4e004aaac42330a5dd2883204988cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae58814e4ebe69e5938513baad4b72191">getDataSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of ProfileData elements. <a href="#ae58814e4ebe69e5938513baad4b72191">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add7d1a58163462c69e3e02b43485e57b">classof</a> (const InstrProfCorrelator *C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74c2f41a0a3b50b5deb9539ac3496b59">classof</a> (const InstrProfCorrelator *C)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69ac01fb5a8e58ba5dcd203e77b864c3">correlateProfileData</a> (int MaxWarnings) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a ProfileData vector used to correlate raw instrumentation data to their functions. <a href="#a69ac01fb5a8e58ba5dcd203e77b864c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a5a106c1293b36f0e9051d646d4eaa2">correlateProfileDataImpl</a> (int MaxWarnings, InstrProfCorrelator::CorrelationData *Data=nullptr)=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e1fcb14f9a46a37bd5c5e694ce93200">correlateProfileNameImpl</a> ()=0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac405f176b874b2cd1972cce9e3dd7382">dumpYaml</a> (int MaxWarnings, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info and dump the correlation data. <a href="#ac405f176b874b2cd1972cce9e3dd7382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bff8029ab8d3854f249ac5c2ad2f9e3">addDataProbe</a> (uint64_t FunctionName, uint64_t CFGHash, IntPtrT CounterOffset, IntPtrT FunctionPtr, uint32_t NumCounters)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abab40c355a15eb07bed9a3bca7edb2e8">maybeSwap</a> (T Value) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/rawinstrprof/profiledata">RawInstrProf::ProfileData</a>&lt; IntPtrT &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a416a9d0e25db54b080f624ddd569582a">Data</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">llvm::DenseSet</a>&lt; IntPtrT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ad0cdfb18fdb700540de21c93555945">CounterOffsets</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a892a9f42e8f35325931654ddb70595c7">classof</a> (const InstrProfCorrelator *C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class IntPtrT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03623c93978bf24485c895a53d164368">get</a> (std::unique_ptr&lt; InstrProfCorrelator::Context &gt; Ctx, const object::ObjectFile &amp;Obj, ProfCorrelatorKind FileKind) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a>&lt; IntPtrT &gt; &gt; &gt;</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl">InstrProfCorrelatorImpl</a> - A child of <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> with a template pointer type so that the ProfileData vector can be materialized.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrProfCorrelatorImpl() {#a9110dae8cefc94bca7e5f15b038b2d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binaryinstrprofcorrelator/#a9a4f4600ec30ccc7b2fe6d75dc774ab5">llvm::BinaryInstrProfCorrelator&lt; IntPtrT &gt;::BinaryInstrProfCorrelator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfinstrprofcorrelator/#a5c0d4ad038bb0679b8e58456ff7e21e2">llvm::DwarfInstrProfCorrelator&lt; IntPtrT &gt;::DwarfInstrProfCorrelator</a> and <a href="#afcaf567d257fbc2765841a650dfbea39">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a>.</p>

</div>
</div>

### InstrProfCorrelatorImpl() {#afcaf567d257fbc2765841a650dfbea39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfCorrelatorImpl&lt; uint32_t &gt;::InstrProfCorrelatorImpl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aacbf16aca287c7491c678a6f132873c5a0da63906732947731d2b0fe9f8c6cd2f">llvm::InstrProfCorrelator::CK_32Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>, <a href="#a9110dae8cefc94bca7e5f15b038b2d6a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### InstrProfCorrelatorImpl() {#adf8cb0ea37a236a4e14082085f9871af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfCorrelatorImpl&lt; uint64_t &gt;::InstrProfCorrelatorImpl (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aacbf16aca287c7491c678a6f132873c5a78613e0199a199b50f3f437128c1c6e3">llvm::InstrProfCorrelator::CK_64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>, <a href="#a9110dae8cefc94bca7e5f15b038b2d6a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### InstrProfCorrelatorImpl() {#a029f808eb3fc90fb806ca0f966499fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::InstrProfCorrelatorImpl (<a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aacbf16aca287c7491c678a6f132873c5">InstrProfCorrelatorKind</a> Kind, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### classof() {#add7d1a58163462c69e3e02b43485e57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfCorrelatorImpl&lt; uint32_t &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aacbf16aca287c7491c678a6f132873c5a0da63906732947731d2b0fe9f8c6cd2f">llvm::InstrProfCorrelator::CK_32Bit</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#a340992f098d86dcc24bdaf9f198f0008">llvm::InstrProfCorrelator::InstrProfCorrelator</a>.</p>

</div>
</div>

### classof() {#a74c2f41a0a3b50b5deb9539ac3496b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfCorrelatorImpl&lt; uint64_t &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aacbf16aca287c7491c678a6f132873c5a78613e0199a199b50f3f437128c1c6e3">llvm::InstrProfCorrelator::CK_64Bit</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#a340992f098d86dcc24bdaf9f198f0008">llvm::InstrProfCorrelator::InstrProfCorrelator</a>.</p>

</div>
</div>

### getDataPointer() {#aa4e004aaac42330a5dd2883204988cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RawInstrProf::ProfileData&lt; IntPtrT &gt; * llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::getDataPointer ()</td>
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

<p>Return a pointer to the underlying ProfileData vector that this class constructs.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>.</p>

</div>
</div>

### getDataSize() {#ae58814e4ebe69e5938513baad4b72191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::getDataSize ()</td>
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

<p>Return the number of ProfileData elements.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addDataProbe() {#a9bff8029ab8d3854f249ac5c2ad2f9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfCorrelatorImpl::addDataProbe (uint64_t FunctionName, uint64_t CFGHash, IntPtrT CounterOffset, IntPtrT FunctionPtr, uint32_t NumCounters)</td>
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



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>, <a href="#abab40c355a15eb07bed9a3bca7edb2e8">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::maybeSwap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a435d7554367e426f8c41efd8c1f70ab0">llvm::NumCounters</a>.</p>

</div>
</div>

### correlateProfileData() {#a69ac01fb5a8e58ba5dcd203e77b864c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfCorrelatorImpl::correlateProfileData (int MaxWarnings)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a ProfileData vector used to correlate raw instrumentation data to their functions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWarnings</td>
<td class="doxyParamItemDescription"><p>the maximum number of warnings to emit (0 = no limit)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2a5a106c1293b36f0e9051d646d4eaa2">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileDataImpl</a>, <a href="#a1e1fcb14f9a46a37bd5c5e694ce93200">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileNameImpl</a>, <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#a8708967ee1eb68916b2b81d12dd2b17d">llvm::InstrProfCorrelator::Names</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#a8152ecdc21d95b563f3de52c8f5993cd">llvm::InstrProfCorrelator::NamesVec</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2ab0ff9f82990293dc09df4d7283c5dd">llvm::unable_to_correlate_profile</a>.</p>

</div>
</div>

### correlateProfileDataImpl() {#a2a5a106c1293b36f0e9051d646d4eaa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileDataImpl (int MaxWarnings, <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/correlationdata">InstrProfCorrelator::CorrelationData</a> * Data=nullptr)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>.</p>


<p>Referenced by <a href="#a69ac01fb5a8e58ba5dcd203e77b864c3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileData</a> and <a href="#ac405f176b874b2cd1972cce9e3dd7382">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::dumpYaml</a>.</p>

</div>
</div>

### correlateProfileNameImpl() {#a1e1fcb14f9a46a37bd5c5e694ce93200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileNameImpl ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a435d7554367e426f8c41efd8c1f70ab0">llvm::NumCounters</a>.</p>


<p>Referenced by <a href="#a69ac01fb5a8e58ba5dcd203e77b864c3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileData</a>.</p>

</div>
</div>

### dumpYaml() {#ac405f176b874b2cd1972cce9e3dd7382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfCorrelatorImpl::dumpYaml (int MaxWarnings, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> debug info and dump the correlation data.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxWarnings</td>
<td class="doxyParamItemDescription"><p>the maximum number of warnings to emit (0 = no limit)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="#a2a5a106c1293b36f0e9051d646d4eaa2">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileDataImpl</a>, <a href="#a416a9d0e25db54b080f624ddd569582a">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2ab0ff9f82990293dc09df4d7283c5dd">llvm::unable_to_correlate_profile</a>.</p>

</div>
</div>

### maybeSwap() {#abab40c355a15eb07bed9a3bca7edb2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::maybeSwap (T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a9bff8029ab8d3854f249ac5c2ad2f9e3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::addDataProbe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Data {#a416a9d0e25db54b080f624ddd569582a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;RawInstrProf::ProfileData&lt;IntPtrT&gt; &gt; llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::Data</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>Referenced by <a href="#a9bff8029ab8d3854f249ac5c2ad2f9e3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::addDataProbe</a>, <a href="#a69ac01fb5a8e58ba5dcd203e77b864c3">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileData</a>, <a href="#a2a5a106c1293b36f0e9051d646d4eaa2">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::correlateProfileDataImpl</a>, <a href="#ac405f176b874b2cd1972cce9e3dd7382">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::dumpYaml</a>, <a href="#aa4e004aaac42330a5dd2883204988cf5">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::getDataPointer</a> and <a href="#ae58814e4ebe69e5938513baad4b72191">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::getDataSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CounterOffsets {#a4ad0cdfb18fdb700540de21c93555945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseSet&lt;IntPtrT&gt; llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::CounterOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a892a9f42e8f35325931654ddb70595c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator">InstrProfCorrelator</a> * C)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#a340992f098d86dcc24bdaf9f198f0008">llvm::InstrProfCorrelator::InstrProfCorrelator</a>.</p>

</div>
</div>

### get() {#a03623c93978bf24485c895a53d164368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class IntPtrT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; InstrProfCorrelatorImpl&lt; IntPtrT &gt; &gt; &gt; InstrProfCorrelatorImpl::get (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/instrprofcorrelator/context">InstrProfCorrelator::Context</a> &gt; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aa6c294f873ca4a3787ea1141651a50bc">ProfCorrelatorKind</a> FileKind)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ac9e9fa2e8b9f1243b2f9b970dc245bef">llvm::InstrProfCorrelator::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#aa6c294f873ca4a3787ea1141651a50bca1286d41436cfb2b7552cfc78df6a6d58">llvm::InstrProfCorrelator::DEBUG_INFO</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ae470b1ff27e3d72e61fcb4a97fd0a461">llvm::object::Binary::isELF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a81663775ec5f9cc32d3d2d15815effbd">llvm::object::Binary::isMachO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a2ab0ff9f82990293dc09df4d7283c5dd">llvm::unable_to_correlate_profile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofcorrelator-h">InstrProfCorrelator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp">InstrProfCorrelator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
