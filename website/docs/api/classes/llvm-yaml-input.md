---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/input
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Input` Class

<p>The <a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a> class is used to parse a yaml document into in-memory structs and vectors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::Input { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86258e41539d20c5f42e0d0d91a0dc4b">Input</a> (StringRef InputContent, void *Ctxt=nullptr, SourceMgr::DiagHandlerTy DiagHandler=nullptr, void *DiagHandlerCtxt=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce204b21e8b3fcedb406b542ba72a48">Input</a> (MemoryBufferRef Input, void *Ctxt=nullptr, SourceMgr::DiagHandlerTy DiagHandler=nullptr, void *DiagHandlerCtxt=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751a00f715dcf146dbe0e592bda70e82">~Input</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa353fb192bcd1d2e0561858ad440829b">error</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fe8d0bc6e86529501a7ff2867fa1a7">setCurrentDocument</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ce7da8d438cf158c9b36d433ad386d">nextDocument</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d0f73828b60339a98e96c60f4b0a4b">getCurrentNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current node that's being parsed by the YAML Parser. <a href="#ae0d0f73828b60339a98e96c60f4b0a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5215e9d17e10644943433af89b5f3a03">setAllowUnknownKeys</a> (bool Allow) override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697c2275dd1227ab9698d59824b091a4">outputting</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e823d85fa987a6942b0c6dd75b3894">mapTag</a> (StringRef, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3af5d3f77cc29073f9914af6afecd1">beginMapping</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0115d7079262eb2a831bb2566d94a5e8">endMapping</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb9df865b5f6b62666736089d20ea8d">preflightKey</a> (const char *, bool, bool, bool &amp;, void *&amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af742d77d539902d9466f8ef431354baf">postflightKey</a> (void *) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad890ea50fa8ec0938f86015b82af58e5">keys</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268a3b5e892d056b710ecd3857ac70ab">beginFlowMapping</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af44dd33a703c56d3692cd88dc6a7af">endFlowMapping</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7786148cab15a41ed1b48b0086f287c0">beginSequence</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1778a36854809b8ff43545904082431e">endSequence</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14ee5f886646ea57bfadd1e43599989">preflightElement</a> (unsigned index, void *&amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d96f3ea2c6a06370ab43a541f3cf1fa">postflightElement</a> (void *) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f75d4291398b4877f8961c19bb1d991">beginFlowSequence</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0a1149250ec2ff3d939e5e72974222">preflightFlowElement</a> (unsigned, void *&amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9919f934a68b56058b026668443387e5">postflightFlowElement</a> (void *) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370bbb42f967c30e2f64681aa5f69c68">endFlowSequence</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0049e603f9259acc29d835161ed1cf">beginEnumScalar</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a8dc99f3d4237535dc7b5b52c1a42f">matchEnumScalar</a> (const char *, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862a823be23e99702f409fd5d16f8de8">matchEnumFallback</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a487f98c3b382d691cdc71341e08cf7cc">endEnumScalar</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee13c907e0220d4932e0eb96b2746168">beginBitSetScalar</a> (bool &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6fa18e0b3b4bd5b7a8091ea3fb5da14">bitSetMatch</a> (const char *, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af868865a2cfceb56ecb4605a7f48460f">endBitSetScalar</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa317ce80ad0e730cd47b6d16ba049c35">scalarString</a> (StringRef &amp;, QuotingType) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267854f902373776b4e5ece719067218">blockScalarString</a> (StringRef &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ed70e77948c40db2248308f260bf02">scalarTag</a> (std::string &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3d">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91068b2bce59a76fb021c7456ef0065">getNodeKind</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1224d59022a6984399311882f5666e1">setError</a> (const Twine &amp;message) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6757f636725e5b0123f57040086a4e8">canElideEmptySequence</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Input::HNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc832e4336a19392399564d1e08d816d">createHNodes</a> (Node *node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aaf3dc5d764abb84bad4b5d30190f86">setError</a> (HNode *hnode, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c80e91912dea34c8e6c7b892352d43">setError</a> (Node *node, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36dfdd781f9a0dd5f15a78fe8dff35a1">setError</a> (const SMRange &amp;Range, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a1d617538d1cb3dfeda21571b57680">reportWarning</a> (HNode *hnode, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c18c1c5e1c2bcaebadcd23e8cc0b1d">reportWarning</a> (Node *hnode, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c18c990905e8091f1c1bf842c90ea35">reportWarning</a> (const SMRange &amp;Range, const Twine &amp;message)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8eb03f67bc18ae2b64da4db7cf78841">releaseHNodeBuffers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release memory used by HNodes. <a href="#aa8eb03f67bc18ae2b64da4db7cf78841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35a6c68e7a5677ef29c143f407ed554">SrcMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/stream">llvm::yaml::Stream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf09e76d85fbacde35d74351ab013633">Strm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b4962b18b48877f4ee92a5fa97ee8a">TopNode</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60045e3bee5d5d2a6861848f606cc1fa">EC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b23e960ca5d69bd48365aa24b917c79">StringAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; EmptyHNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e379d82abda1fe312c37262c8ef1791">EmptyHNodeAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; ScalarHNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefea1b24a4a51a1ab0076d564152b6e3">ScalarHNodeAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; MapHNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e4dff306cf6f024642af05e3deab28">MapHNodeAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; SequenceHNode &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20bce4874cd3112f81c1fef5e7257cca">SequenceHNodeAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/document-iterator">document_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04c3cf9aa6d48d0a1d12cf4fd77000a">DocIterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">llvm::BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041334b0e91c732469d44f0763dcd258">BitValuesUsed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04316b9c283818c982011dc325e31dfc">CurrentNode</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ead2154b164360d12105bb62459b202">ScalarMatchFound</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ca040e57b2ff96fbe07254eee58791">AllowUnknownKeys</a> = false</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a> class is used to parse a yaml document into in-memory structs and vectors.</p>


<p>It works by using YAMLParser to do a syntax parse of the entire yaml document, then the <a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a> class builds a graph of HNodes which wraps each yaml <a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a>. The extra layer is buffering. The low level yaml parser only lets you look at each node once. The buffering layer lets you search and interate multiple times. This is necessary because the <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">mapRequired()</a> method calls may not be in the same order as the keys in the document.</p>


<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Input() {#a86258e41539d20c5f42e0d0d91a0dc4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Input::Input (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputContent, void * Ctxt=nullptr, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">SourceMgr::DiagHandlerTy</a> DiagHandler=nullptr, void * DiagHandlerCtxt=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#af6a69e8083e27fcd02a6573b3d648f8d">llvm::yaml::IO::IO</a>.</p>


<p>Referenced by <a href="#a7ce204b21e8b3fcedb406b542ba72a48">Input</a>.</p>

</div>
</div>

### Input() {#a7ce204b21e8b3fcedb406b542ba72a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Input::Input (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Input, void * Ctxt=nullptr, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">SourceMgr::DiagHandlerTy</a> DiagHandler=nullptr, void * DiagHandlerCtxt=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>, <a href="#a86258e41539d20c5f42e0d0d91a0dc4b">Input</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#af6a69e8083e27fcd02a6573b3d648f8d">llvm::yaml::IO::IO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Input() {#a751a00f715dcf146dbe0e592bda70e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Input::~Input ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### error() {#aa353fb192bcd1d2e0561858ad440829b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code Input::error ()</td>
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



<p>Declaration at line 1452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a805f6e017afb868ed3f50b1b76d35468">llvm::yaml::convertYAML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hsamd/#a3a88349f84d4691e26a0a7f9c26be0a9">llvm::AMDGPU::HSAMD::fromString</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#abec5174f9edec79de20397f6b8e0ccdf">llvm::msgpack::Document::fromYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapireader/#ae720a98705c6ad89165018117560dc47">llvm::MachO::TextAPIReader::get</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/callsiteinfoloader/#af96a5f4033bb285a8570b073578aceb1">llvm::gsym::CallSiteInfoLoader::loadYAML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a770c190bd3958ba4bab019740436307f">llvm::yaml::operator&gt;&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#aa050d96fe18573b4d459a769f576f1dc">llvm::memprof::YAMLMemProfReader::parse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a4a9a9da06942147f34ff61f3f3efb389">llvm::ifs::readIFSFromBuffer</a>.</p>

</div>
</div>

### getCurrentNode() {#ae0d0f73828b60339a98e96c60f4b0a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Node * Input::getCurrentNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the current node that's being parsed by the YAML Parser.</p>

<p>Declaration at line 1569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### nextDocument() {#a19ce7da8d438cf158c9b36d433ad386d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::nextDocument ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a805f6e017afb868ed3f50b1b76d35468">llvm::yaml::convertYAML</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2224262c0507515a54edc38eb71d693c">llvm::OutlinedHashTreeRecord::deserializeYAML</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#add85723c9058d7160e140ca778136076">llvm::StableFunctionMapRecord::deserializeYAML</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a770c190bd3958ba4bab019740436307f">llvm::yaml::operator&gt;&gt;</a>.</p>

</div>
</div>

### setAllowUnknownKeys() {#a5215e9d17e10644943433af89b5f3a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::setAllowUnknownKeys (bool Allow)</td>
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



<p>Declaration at line 1571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### setCurrentDocument() {#ab0fe8d0bc6e86529501a7ff2867fa1a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::setCurrentDocument ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ab0fe8d0bc6e86529501a7ff2867fa1a7">setCurrentDocument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a770c190bd3958ba4bab019740436307f">llvm::yaml::operator&gt;&gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a456396a154e3594cf72fa645f82d3d17">llvm::yaml::operator&gt;&gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a3c24198f2302e5b34244cf54a8cbca80">llvm::yaml::operator&gt;&gt;</a> and <a href="#ab0fe8d0bc6e86529501a7ff2867fa1a7">setCurrentDocument</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### beginBitSetScalar() {#aee13c907e0220d4932e0eb96b2746168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::beginBitSetScalar (bool &amp; DoClear)</td>
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



<p>Declaration at line 1476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### beginEnumScalar() {#a9c0049e603f9259acc29d835161ed1cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::beginEnumScalar ()</td>
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



<p>Declaration at line 1472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### beginFlowMapping() {#a268a3b5e892d056b710ecd3857ac70ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::beginFlowMapping ()</td>
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



<p>Declaration at line 1462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### beginFlowSequence() {#a9f75d4291398b4877f8961c19bb1d991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Input::beginFlowSequence ()</td>
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



<p>Declaration at line 1468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### beginMapping() {#a0f3af5d3f77cc29073f9914af6afecd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::beginMapping ()</td>
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



<p>Declaration at line 1457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### beginSequence() {#a7786148cab15a41ed1b48b0086f287c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Input::beginSequence ()</td>
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



<p>Declaration at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### bitSetMatch() {#aa6fa18e0b3b4bd5b7a8091ea3fb5da14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::bitSetMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, bool)</td>
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



<p>Declaration at line 1477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### blockScalarString() {#a267854f902373776b4e5ece719067218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::blockScalarString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; S)</td>
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



<p>Declaration at line 1480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### canElideEmptySequence() {#ac6757f636725e5b0123f57040086a4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::canElideEmptySequence ()</td>
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



<p>Declaration at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### createHNodes() {#acc832e4336a19392399564d1e08d816d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Input::HNode * Input::createHNodes (<a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> * node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endBitSetScalar() {#af868865a2cfceb56ecb4605a7f48460f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endBitSetScalar ()</td>
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



<p>Declaration at line 1478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endEnumScalar() {#a487f98c3b382d691cdc71341e08cf7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endEnumScalar ()</td>
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



<p>Declaration at line 1475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endFlowMapping() {#a0af44dd33a703c56d3692cd88dc6a7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endFlowMapping ()</td>
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



<p>Declaration at line 1463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endFlowSequence() {#a370bbb42f967c30e2f64681aa5f69c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endFlowSequence ()</td>
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



<p>Declaration at line 1471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endMapping() {#a0115d7079262eb2a831bb2566d94a5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endMapping ()</td>
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



<p>Declaration at line 1458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### endSequence() {#a1778a36854809b8ff43545904082431e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::endSequence ()</td>
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



<p>Declaration at line 1465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### getNodeKind() {#ac91068b2bce59a76fb021c7456ef0065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind Input::getNodeKind ()</td>
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



<p>Declaration at line 1482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### keys() {#ad890ea50fa8ec0938f86015b82af58e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StringRef &gt; Input::keys ()</td>
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



<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### mapTag() {#ad0e823d85fa987a6942b0c6dd75b3894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::mapTag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag, bool Default)</td>
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



<p>Declaration at line 1456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### matchEnumFallback() {#a862a823be23e99702f409fd5d16f8de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::matchEnumFallback ()</td>
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



<p>Declaration at line 1474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### matchEnumScalar() {#af0a8dc99f3d4237535dc7b5b52c1a42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::matchEnumScalar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, bool)</td>
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



<p>Declaration at line 1473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### outputting() {#a697c2275dd1227ab9698d59824b091a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::outputting ()</td>
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



<p>Declaration at line 1455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### postflightElement() {#a9d96f3ea2c6a06370ab43a541f3cf1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::postflightElement (void * SaveInfo)</td>
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



<p>Declaration at line 1467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### postflightFlowElement() {#a9919f934a68b56058b026668443387e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::postflightFlowElement (void * SaveInfo)</td>
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



<p>Declaration at line 1470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### postflightKey() {#af742d77d539902d9466f8ef431354baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::postflightKey (void * saveInfo)</td>
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



<p>Declaration at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### preflightElement() {#ac14ee5f886646ea57bfadd1e43599989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::preflightElement (unsigned index, void *&amp; SaveInfo)</td>
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



<p>Declaration at line 1466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### preflightFlowElement() {#acf0a1149250ec2ff3d939e5e72974222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::preflightFlowElement (unsigned index, void *&amp; SaveInfo)</td>
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



<p>Declaration at line 1469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### preflightKey() {#a2fb9df865b5f6b62666736089d20ea8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Input::preflightKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, bool Required, bool, bool &amp; UseDefault, void *&amp; SaveInfo)</td>
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



<p>Declaration at line 1459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### releaseHNodeBuffers() {#aa8eb03f67bc18ae2b64da4db7cf78841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::releaseHNodeBuffers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release memory used by HNodes.</p>

<p>Declaration at line 1560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### reportWarning() {#ae2a1d617538d1cb3dfeda21571b57680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::reportWarning (HNode * hnode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### reportWarning() {#a71c18c1c5e1c2bcaebadcd23e8cc0b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::reportWarning (<a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> * hnode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### reportWarning() {#a7c18c990905e8091f1c1bf842c90ea35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::reportWarning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; Range, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### scalarString() {#aa317ce80ad0e730cd47b6d16ba049c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::scalarString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; S, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a>)</td>
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



<p>Declaration at line 1479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### scalarTag() {#a27ed70e77948c40db2248308f260bf02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::scalarTag (std::string &amp; Tag)</td>
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



<p>Declaration at line 1481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### setError() {#ad1224d59022a6984399311882f5666e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
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



<p>Declaration at line 1483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### setError() {#a0aaf3dc5d764abb84bad4b5d30190f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::setError (HNode * hnode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### setError() {#a98c80e91912dea34c8e6c7b892352d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::setError (<a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> * node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

### setError() {#a36dfdd781f9a0dd5f15a78fe8dff35a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Input::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; Range, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllowUnknownKeys {#a56ca040e57b2ff96fbe07254eee58791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Input::AllowUnknownKeys = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### BitValuesUsed {#a041334b0e91c732469d44f0763dcd258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitVector llvm::yaml::Input::BitValuesUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### CurrentNode {#a04316b9c283818c982011dc325e31dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HNode* llvm::yaml::Input::CurrentNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### DocIterator {#ad04c3cf9aa6d48d0a1d12cf4fd77000a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">document_iterator llvm::yaml::Input::DocIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### EC {#a60045e3bee5d5d2a6861848f606cc1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::yaml::Input::EC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### EmptyHNodeAllocator {#a6e379d82abda1fe312c37262c8ef1791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;EmptyHNode&gt; llvm::yaml::Input::EmptyHNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### MapHNodeAllocator {#a94e4dff306cf6f024642af05e3deab28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MapHNode&gt; llvm::yaml::Input::MapHNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### ScalarHNodeAllocator {#aefea1b24a4a51a1ab0076d564152b6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;ScalarHNode&gt; llvm::yaml::Input::ScalarHNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### ScalarMatchFound {#a8ead2154b164360d12105bb62459b202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Input::ScalarMatchFound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### SequenceHNodeAllocator {#a20bce4874cd3112f81c1fef5e7257cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;SequenceHNode&gt; llvm::yaml::Input::SequenceHNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### SrcMgr {#ab35a6c68e7a5677ef29c143f407ed554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr llvm::yaml::Input::SrcMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### StringAllocator {#a5b23e960ca5d69bd48365aa24b917c79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::yaml::Input::StringAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### Strm {#acf09e76d85fbacde35d74351ab013633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::yaml::Stream&gt; llvm::yaml::Input::Strm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### TopNode {#a44b4962b18b48877f4ee92a5fa97ee8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HNode* llvm::yaml::Input::TopNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
