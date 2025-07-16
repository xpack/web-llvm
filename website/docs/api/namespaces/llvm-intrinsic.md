---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/intrinsic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Intrinsic` Namespace Reference

<p>This namespace contains an enum with a value for every intrinsic/builtin function known by LLVM. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::Intrinsic { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a type descriptor which explains the type requirements of an intrinsic. <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="#a80add6b3b1cdaec560907995127adc16">ID</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IndependentIntrinsics : unsigned { <a href="#a35fedf4db6d756bd82501607f93c1e79">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MatchIntrinsicTypesResult { <a href="#a27bed4b8203db6bfcaaae8b3221848d0">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7157f9fa9dd11f234ec3c58517cb6d96">getName</a> (ID id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM name for an intrinsic, such as "llvm.ppc.altivec.lvx". <a href="#a7157f9fa9dd11f234ec3c58517cb6d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac36688686cd311fab09e6b55efb7f96">getBaseName</a> (ID id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM name for an intrinsic, without encoded types for overloading, such as "llvm.ssa.copy". <a href="#aac36688686cd311fab09e6b55efb7f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6d8be4a3793bd5cef4d3f25508a4fa">getName</a> (ID Id, ArrayRef&lt; Type * &gt; Tys, Module *M, FunctionType *FT=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM name for an intrinsic, such as "llvm.ppc.altivec.lvx" or "llvm.ssa.copy.p0s_s.1". <a href="#a9a6d8be4a3793bd5cef4d3f25508a4fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2b24ea2831ebf75ab12501d3ca89e8">getNameNoUnnamedTypes</a> (ID Id, ArrayRef&lt; Type * &gt; Tys)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM name for an intrinsic. <a href="#a3b2b24ea2831ebf75ab12501d3ca89e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1828635e30f34e4958afeb5541766e">getType</a> (LLVMContext &amp;Context, ID id, ArrayRef&lt; Type * &gt; Tys={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function type for an intrinsic. <a href="#aca1828635e30f34e4958afeb5541766e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d91e185087b0ac1f22ef439a170c7f">isOverloaded</a> (ID id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the intrinsic can be overloaded. <a href="#ab2d91e185087b0ac1f22ef439a170c7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb05a68bd17abae22344be8a1a41fb5d">isTargetIntrinsic</a> (ID IID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTargetIntrinsic - Returns true if IID is an intrinsic specific to a certain target. <a href="#aeb05a68bd17abae22344be8a1a41fb5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80add6b3b1cdaec560907995127adc16">ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821cf516da0409f54e4cd8a5b7478ea7">lookupIntrinsicID</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This does the actual lookup of an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> which matches the given function name. <a href="#a821cf516da0409f54e4cd8a5b7478ea7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89cda2218259523c41863fc1175d6907">getAttributes</a> (LLVMContext &amp;C, ID id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attributes for an intrinsic. <a href="#a89cda2218259523c41863fc1175d6907">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a> (Module *M, ID id, ArrayRef&lt; Type * &gt; Tys={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> declaration of the intrinsic <span class="doxyComputerOutput">id</span> in the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> <span class="doxyComputerOutput">M</span>. <a href="#a0cff8be0190d8e20b7cf13646f34afa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a163f0f99e34c12ffe66edc4fe4cc2">LLVM_DEPRECATED</a> ("Use getOrInsertDeclaration instead", "getOrInsertDeclaration") inline Function *getDeclaration(Module *M</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1731508126b77035ab3ba9d71d5374b">getDeclarationIfExists</a> (Module *M, ID id, ArrayRef&lt; Type * &gt; Tys, FunctionType *FT=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This version supports overloaded intrinsics. <a href="#aa1731508126b77035ab3ba9d71d5374b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80add6b3b1cdaec560907995127adc16">ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7625b4659e0bcfd1e8938bfc188537c4">getIntrinsicForClangBuiltin</a> (StringRef TargetPrefix, StringRef BuiltinName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a Clang builtin name to an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a>. <a href="#a7625b4659e0bcfd1e8938bfc188537c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80add6b3b1cdaec560907995127adc16">ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7064731c86d5ab52f953e6ccd8322f">getIntrinsicForMSBuiltin</a> (StringRef TargetPrefix, StringRef BuiltinName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a MS builtin name to an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a>. <a href="#a9a7064731c86d5ab52f953e6ccd8322f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff2d64dca44822331bda0a0975ebd6d">isConstrainedFPIntrinsic</a> (ID QID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> is for one of the "Constrained
Floating-Point Intrinsics". <a href="#a7ff2d64dca44822331bda0a0975ebd6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbd4447f1241859563534da87edfa1f">hasConstrainedFPRoundingModeOperand</a> (ID QID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> is for one of the "Constrained
Floating-Point Intrinsics" that take rounding mode metadata. <a href="#a3dbd4447f1241859563534da87edfa1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264036c4b5fffd4ce40a5414d587d26b">getIntrinsicInfoTableEntries</a> (ID id, SmallVectorImpl&lt; IITDescriptor &gt; &amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the IIT table descriptor for the specified intrinsic into an array of IITDescriptors. <a href="#a264036c4b5fffd4ce40a5414d587d26b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a27bed4b8203db6bfcaaae8b3221848d0">MatchIntrinsicTypesResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dfad57f1487bb34ef68784a2e878c8">matchIntrinsicSignature</a> (FunctionType *FTy, ArrayRef&lt; IITDescriptor &gt; &amp;Infos, SmallVectorImpl&lt; Type * &gt; &amp;ArgTys)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match the specified function type with the type constraints specified by the .td file. <a href="#a17dfad57f1487bb34ef68784a2e878c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8db50c76878b9d7747a77ecdeadbb48">matchIntrinsicVarArg</a> (bool isVarArg, ArrayRef&lt; IITDescriptor &gt; &amp;Infos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if the intrinsic has variable arguments. <a href="#af8db50c76878b9d7747a77ecdeadbb48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a> (Intrinsic::ID, FunctionType *FT, SmallVectorImpl&lt; Type * &gt; &amp;ArgTys)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the type arguments of an intrinsic call by matching type contraints specified by the .td file. <a href="#adce8df27d44de3e02c13209348660f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720100fe2ad7a57ecd75a4f80f8b766c">getIntrinsicSignature</a> (Function *F, SmallVectorImpl&lt; Type * &gt; &amp;ArgTys)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as previous, but accepts a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> instead of <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>. <a href="#a720100fe2ad7a57ecd75a4f80f8b766c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">remangleIntrinsicFunction</a> (Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93df8888c3b6eb4e7e5df51033799693">NoAliasScopeDeclScopeArg</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80add6b3b1cdaec560907995127adc16">ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd225da5fcb670947a8e869fce8650e">id</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a80add6b3b1cdaec560907995127adc16">ID</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a> = ...</td>
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

<p>This namespace contains an enum with a value for every intrinsic/builtin function known by LLVM.</p>


<p>The enum values are returned by <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">Function::getIntrinsicID()</a>.</p>


<div class="doxySectionDef">

## Typedefs

### ID {#a80add6b3b1cdaec560907995127adc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned llvm::Intrinsic::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### IndependentIntrinsics {#a35fedf4db6d756bd82501607f93c1e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Intrinsic::IndependentIntrinsics : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">not_intrinsic<a id="a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### MatchIntrinsicTypesResult {#a27bed4b8203db6bfcaaae8b3221848d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Intrinsic::MatchIntrinsicTypesResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchIntrinsicTypes_Match<a id="a27bed4b8203db6bfcaaae8b3221848d0a4283590df1fd295c1e554a6a8054e7eb"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchIntrinsicTypes_NoMatchRet<a id="a27bed4b8203db6bfcaaae8b3221848d0a46acb90eff8458aef3ddf5a4bc3df71b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchIntrinsicTypes_NoMatchArg<a id="a27bed4b8203db6bfcaaae8b3221848d0a4e4a54ec49f8bcc339277046f94588ba"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getAttributes() {#a89cda2218259523c41863fc1175d6907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::Intrinsic::getAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attributes for an intrinsic.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a41d7c53499da41b1739015f7036cf6da">llvm::MachineIRBuilder::buildIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af77a6b87eef9b3173d765b97ceb6c5fb">llvm::SITargetLowering::computeKnownAlignForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a97d7bb2d0dc7b8e471e481ef8e4d3986">stripNonValidAttributesFromPrototype</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d04adf21012419a4bfcd24e75f85a9a">llvm::UpgradeIntrinsicFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a2ba6472d6c916233f98bf13155d959bf">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyGIntrinsicConvergence</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a65af2646bf1b0db3340b48e472c7194c">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyGIntrinsicSideEffects</a>.</p>

</div>
</div>

### getBaseName() {#aac36688686cd311fab09e6b55efb7f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Intrinsic::getBaseName (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM name for an intrinsic, without encoded types for overloading, such as "llvm.ssa.copy".</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1fd225da5fcb670947a8e869fce8650e">id</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a449df9ae61690e8eb01fea5338bcd53d">llvm::VPWidenIntrinsicRecipe::getIntrinsicName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a>, <a href="#a7157f9fa9dd11f234ec3c58517cb6d96">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a59192c42d4cbf804fbcc1deff8edb614">llvm::SDNode::getOperationName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a> and <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4cf50167dfbcc11002f483718ac75556">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::writeFnName</a>.</p>

</div>
</div>

### getDeclarationIfExists() {#aa1731508126b77035ab3ba9d71d5374b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Intrinsic::getDeclarationIfExists (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This version supports overloaded intrinsics.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a52e95fe46f358afc3b0006f256f9d487">computeVirtualCallSiteTypeInfoMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a3ca28a37cc6f2fdfc1a57471623dd411">containsProfilingIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#aeee7951092aa5ce8f95ecb2f03d42893">explicifyGuards</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulowerkernelattributes-cpp-/#aacdc4383087b03e687cc89e6a14147c7">anonymous{AMDGPULowerKernelAttributes.cpp}::getBasePtrIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerguardintrinsic-cpp/#a6c30165ed98029182d00cb428a64fd29">lowerGuardIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerwidenablecondition-cpp/#adb00c4c46ce23c327d6cf77f723255ee">lowerWidenableCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a363028d7884038c73a4f3f2474530c33">anonymous{WholeProgramDevirt.cpp}::DevirtModule::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a5b6fe6d57aa5475337994b0daec8cc54">llvm::JumpThreadingPass::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-looppredication-cpp-/looppredication/#a037f8481d5dc0c43741972ede1461d86">anonymous{LoopPredication.cpp}::LoopPredication::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3f0118e315585ef6debe98a13336ae75">llvm::ScalarEvolution::ScalarEvolution</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#a93898976321fdcdb6827b4885b0d435c">splitGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a>.</p>

</div>
</div>

### getIntrinsicForClangBuiltin() {#a7625b4659e0bcfd1e8938bfc188537c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ID llvm::Intrinsic::getIntrinsicForClangBuiltin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetPrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BuiltinName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a Clang builtin name to an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a>.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### getIntrinsicForMSBuiltin() {#a9a7064731c86d5ab52f953e6ccd8322f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ID llvm::Intrinsic::getIntrinsicForMSBuiltin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetPrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BuiltinName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a MS builtin name to an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a>.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### getIntrinsicInfoTableEntries() {#a264036c4b5fffd4ce40a5414d587d26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Intrinsic::getIntrinsicInfoTableEntries (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a> &gt; &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the IIT table descriptor for the specified intrinsic into an array of IITDescriptors.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aef9c35f13cf93ffcc6bafb8a210d842e">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a> and <a href="#aca1828635e30f34e4958afeb5541766e">getType</a>.</p>

</div>
</div>

### getIntrinsicSignature() {#adce8df27d44de3e02c13209348660f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::getIntrinsicSignature (<a href="#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; ArgTys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the type arguments of an intrinsic call by matching type contraints specified by the .td file.</p>


<p>The overloaded types are pushed into the AgTys vector.</p>


<p>Returns false if the given <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> and function type combination is not a valid intrinsic call.</p>


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="#a264036c4b5fffd4ce40a5414d587d26b">getIntrinsicInfoTableEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="#a17dfad57f1487bb34ef68784a2e878c8">matchIntrinsicSignature</a>, <a href="#a27bed4b8203db6bfcaaae8b3221848d0a4283590df1fd295c1e554a6a8054e7eb">MatchIntrinsicTypes_Match</a> and <a href="#af8db50c76878b9d7747a77ecdeadbb48">matchIntrinsicVarArg</a>.</p>


<p>Referenced by <a href="#a720100fe2ad7a57ecd75a4f80f8b766c">getIntrinsicSignature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">remangleIntrinsicFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>.</p>

</div>
</div>

### getIntrinsicSignature() {#a720100fe2ad7a57ecd75a4f80f8b766c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::getIntrinsicSignature (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; ArgTys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as previous, but accepts a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> instead of <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a>.</p>

</div>
</div>

### getName() {#a7157f9fa9dd11f234ec3c58517cb6d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Intrinsic::getName (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM name for an intrinsic, such as "llvm.ppc.altivec.lvx".</p>


<p>Note, this version is for intrinsics with no overloads. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the other version of getName if overloads are required.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aac36688686cd311fab09e6b55efb7f96">getBaseName</a> and <a href="#ab2d91e185087b0ac1f22ef439a170c7f">isOverloaded</a>.</p>


<p>Referenced by <a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga9537e3801e0a920c4af76a4360baa99b">LLVMIntrinsicCopyOverloadedName2</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga309eb2a3dcfda4477f7361333f099569">LLVMIntrinsicGetName</a>, <a href="#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">remangleIntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a>.</p>

</div>
</div>

### getName() {#a9a6d8be4a3793bd5cef4d3f25508a4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Intrinsic::getName (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM name for an intrinsic, such as "llvm.ppc.altivec.lvx" or "llvm.ssa.copy.p0s_s.1".</p>


<p>Note, this version of getName supports overloads. This is less efficient than the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> version of this function. If no overloads are required, it is safe to use this version, but better to use the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> version. If one of the types is based on an unnamed type, a function type will be computed. Providing FT will avoid this computation.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>

</div>
</div>

### getNameNoUnnamedTypes() {#a3b2b24ea2831ebf75ab12501d3ca89e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Intrinsic::getNameNoUnnamedTypes (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM name for an intrinsic.</p>


<p>This is a special version only to be used by LLVMIntrinsicCopyOverloadedName. It only supports overloads based on named types.</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga6171239b06f741cd21a74f4d45b751f6">LLVMIntrinsicCopyOverloadedName</a>.</p>

</div>
</div>

### getOrInsertDeclaration() {#a0cff8be0190d8e20b7cf13646f34afa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Intrinsic::getOrInsertDeclaration (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> declaration of the intrinsic <span class="doxyComputerOutput">id</span> in the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> <span class="doxyComputerOutput">M</span>.</p>


<p>If it does not exist, add a declaration and return it. Otherwise, return the existing declaration.</p>


<p>The <span class="doxyComputerOutput">Tys</span> parameter is for intrinsics with overloaded types (e.g., those using iAny, fAny, vAny, or pAny). For a declaration of an overloaded intrinsic, Tys must provide exactly one type for each overloaded type in the intrinsic.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#a7157f9fa9dd11f234ec3c58517cb6d96">getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1542efe32b9a597a7d72d3b205dab176">convertToRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3e128b0b1ee770ce64350445c12492c7">llvm::IRBuilderBase::CreateAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ae5881267e88ebfd0527460a92b61f960">llvm::MatrixBuilder::CreateColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a69138108d0e5888e6cafcdd27d082fc8">llvm::MatrixBuilder::CreateColumnMajorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ad623ba85ece2827b2a9c853e95ee24fc">createCoroSave</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#adc686ba917c4b589803df62f9a0c75d6">llvm::DbgLabelRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aef9c35f13cf93ffcc6bafb8a210d842e">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0fb8bf2cae796307f012fc621678642f">llvm::IRBuilderBase::CreateLaunderInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ac4d302983f7d34c7555b016c5901341a">llvm::MatrixBuilder::CreateMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9f3d0f2901feeff9d52b95e58fbb49b">llvm::IRBuilderBase::CreateStripInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9ac45fd1485e6735d83544e54fb52d4b">llvm::IRBuilderBase::CreateUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a69d0103b83202f0339cfb6b018b3c78a">llvm::IRBuilderBase::CreateVectorReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3de426ba33675f047a941f656b33341b">llvm::IRBuilderBase::CreateVectorSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a683761fbb11ed0969edf7eee08b08bf3">llvm::PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#aeee7951092aa5ce8f95ecb2f03d42893">explicifyGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a76d4e1301c34b44df3c6721266d5f38a">factorizeMinMaxTree</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae3ba7f841807b297e7c28874c285f538">foldBitwiseLogicWithIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5bdf52f90e0c8cf28eff0caf18654e0f">foldOverflowingAddSubSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aa231edc47a3993eaf9c7aa2bb324e2f5">foldSelectFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a1bf4aeb6f1b186d451eb7f2536b76c2e">foldSelectToCopysign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a45188914d3b4b24a4a4d7898750b893f">foldSubOfMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#ae1dbc1b5659db932b873f4e0c0e72422">foldToUnsignedSaturatedAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a26105b2c5dc3071155303a10ef8c3923">foldVectorCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a777bef8b513df8776aec8f3cf9ce066b">llvm::InstCombinerImpl::foldVectorSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a9cf59960e7146dd283b2f23753a00c3c">llvm::memtag::getAndroidSlotPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a2607e2337fc3a69c867344fc4e3d209b">getDeclareIntrin</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a45499cf71e7324771b2faa3921da99bb">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getLdexpF32</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#abcfa2b533145fedf69b3e10bc2a30fb6">llvm::VPIntrinsic::getOrInsertDeclarationForParams</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a20b2cf2d81b88d6e6c40a523245424ea">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getSqrtF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a53500398705be6af72f415a563af78a0">getStructuredLoadFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7d366eb4d40575891069ef79b2f9a3bd">getStructuredStoreFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a915a8d23e084b7a40475a3ce2245495b">llvm::DIBuilder::insertDbgValueIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#adee485b8d8a010d18877f5f41286b079">llvm::BPFCoreSharedInfo::insertPassThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a722d17f2a55dcbd4743919cd6796d733">instCombineSVEAllActive</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/functioninstrumenter/#ad8a93caaba7e38b078b14a134f5f46f8">anonymous{PGOInstrumentation.cpp}::FunctionInstrumenter::instrument</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#gae31cd442e48be38030a97c21a2c49867">LLVMGetIntrinsicDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#ae0084d22d52801bfa6842ae37136468e">lowerExpectAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerguardintrinsic-cpp/#a6c30165ed98029182d00cb428a64fd29">lowerGuardIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a9ca08b7ff5754740b223ca4b90e7041f">makeIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/lowererbase/#a8e44a67be75da70df132c8683575d772">llvm::coro::LowererBase::makeSubFnCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a58e10a8e8f7c27c724cd88a29f2739e5">anonymous{AMDGPUSwLowerLDS.cpp}::markUsedByKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ac800cc10159d350923dc27446b9123f0">matchFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a207ccf3b7552ac06054637cf55e01265">reassociateMinMaxWithConstantInOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="#a3ce5fd3a8d74ecd38fdb5e27f85d2d61">remangleIntrinsicFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9910dce4a3e020d503a0e4062d66646f">llvm::GCNTTIImpl::rewriteIntrinsicWithAddressSpace</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#aafb9808e3b375710c68b44c507cd9c3d">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a08f16f302c998119c978d7ce93b4c569">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::tagAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a2969e8555a2230d375d57d0b49f80229">toSpvOverloadedIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac0a8da35200651179e36ea9764bfcc89">upgradePTESTIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac1f097037c1ae12d77e05dff10cde79f">upgradeX86BF16DPIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aa62b623383246a9c9feae4197c9d6f62">upgradeX86BF16Intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a634253063317c2a283da15093157baae">upgradeX86IntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a93fb6df8473d53eee8879c55910f5425">upgradeX86IntrinsicsWith8BitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a483b5e6a98de2a42f981afe55ba0692b">upgradeX86MaskedFPCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aadfa6a6899cb32e0b249dfe7d5ab904b">UseTlsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa919dd3a390d60e7b3971efe82c0b760">useTpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### getType() {#aca1828635e30f34e4958afeb5541766e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::Intrinsic::getType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the function type for an intrinsic.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#a264036c4b5fffd4ce40a5414d587d26b">getIntrinsicInfoTableEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a042f275033dbeb7761b82e5368e871bf">Tys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a> and <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#gaf963d0f39f7ed2d8442308e89f1d8440">LLVMIntrinsicGetType</a>.</p>

</div>
</div>

### hasConstrainedFPRoundingModeOperand() {#a3dbd4447f1241859563534da87edfa1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::hasConstrainedFPRoundingModeOperand (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> QID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> is for one of the "Constrained
Floating-Point Intrinsics" that take rounding mode metadata.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a48ebbc1e9c11c52c99229d706238ea8a">llvm::IRBuilderBase::CreateConstrainedFPCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9b27960ecdd02de32114ff5a0b13077">llvm::IRBuilderBase::CreateConstrainedFPCast</a> and <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a9ba9cd066476f18d59351934de5ee48d">llvm::ConstrainedFPIntrinsic::getNonMetadataArgCount</a>.</p>

</div>
</div>

### isConstrainedFPIntrinsic() {#a7ff2d64dca44822331bda0a0975ebd6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::isConstrainedFPIntrinsic (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> QID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> is for one of the "Constrained
Floating-Point Intrinsics".</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#addecfc8be63e264d66b907dcdf66d96d">llvm::ConstrainedFPIntrinsic::classof</a> and <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>.</p>

</div>
</div>

### isOverloaded() {#ab2d91e185087b0ac1f22ef439a170c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::isOverloaded (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the intrinsic can be overloaded.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a>, <a href="#a7157f9fa9dd11f234ec3c58517cb6d96">getName</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga8cfe249fbfe5f06962902b9dfa596268">LLVMIntrinsicIsOverloaded</a>, <a href="#a821cf516da0409f54e4cd8a5b7478ea7">lookupIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a> and <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a>.</p>

</div>
</div>

### isTargetIntrinsic() {#aeb05a68bd17abae22344be8a1a41fb5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::isTargetIntrinsic (<a href="#a80add6b3b1cdaec560907995127adc16">ID</a> IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isTargetIntrinsic - Returns true if IID is an intrinsic specific to a certain target.</p>


<p>If it is a generic intrinsic false is returned.</p>


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0283a501ef1d3a463720e9c1deb3811b">llvm::isTriviallyScalarizable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af746db8ff154caf5682df4f99ca97d30">llvm::isVectorIntrinsicWithOverloadTypeAtArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad6db62129ba3650d98ce56fa03ab5f1">llvm::isVectorIntrinsicWithScalarOpAtArg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9e26a2be2e0e9ab378ebbd6b35c381c3">llvm::isVectorIntrinsicWithStructReturnOverloadAtField</a>.</p>

</div>
</div>

### LLVM\_DEPRECATED() {#a15a163f0f99e34c12ffe66edc4fe4cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Intrinsic::LLVM_DEPRECATED ("Use <a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a> instead", "getOrInsertDeclaration")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>

</div>
</div>

### lookupIntrinsicID() {#a821cf516da0409f54e4cd8a5b7478ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::Intrinsic::lookupIntrinsicID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This does the actual lookup of an intrinsic <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> which matches the given function name.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a7abd9a1f2faccb322ee43cd1fb4670d4">findTargetSubtable</a>, <a href="#ab2d91e185087b0ac1f22ef439a170c7f">isOverloaded</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a> and <a href="#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">not_intrinsic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#af1298b18b7e3099c7e9998d9970ec0bc">isOldDbgFormatIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga23bc095aa18029df12ab92ba5a318c6f">LLVMLookupIntrinsicID</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a02ce808485bec6d45ce163e0d50bb061">anonymous{MIParser.cpp}::MIParser::parseIntrinsicOperand</a>.</p>

</div>
</div>

### matchIntrinsicSignature() {#a17dfad57f1487bb34ef68784a2e878c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::MatchIntrinsicTypesResult llvm::Intrinsic::matchIntrinsicSignature (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a> &gt; &amp; Infos, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; ArgTys)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match the specified function type with the type constraints specified by the .td file.</p>


<p>If the given type is an overloaded type it is pushed to the ArgTys vector.</p>


<p>Returns false if the given type matches with the constraints, true otherwise.</p>


<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="#a27bed4b8203db6bfcaaae8b3221848d0a4283590df1fd295c1e554a6a8054e7eb">MatchIntrinsicTypes_Match</a>, <a href="#a27bed4b8203db6bfcaaae8b3221848d0a4e4a54ec49f8bcc339277046f94588ba">MatchIntrinsicTypes_NoMatchArg</a>, <a href="#a27bed4b8203db6bfcaaae8b3221848d0a46acb90eff8458aef3ddf5a4bc3df71b">MatchIntrinsicTypes_NoMatchRet</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a8dc558dee9c54b788dd559fed3c0a39a">llvm::FunctionType::params</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a>.</p>

</div>
</div>

### matchIntrinsicVarArg() {#af8db50c76878b9d7747a77ecdeadbb48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Intrinsic::matchIntrinsicVarArg (bool isVarArg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">IITDescriptor</a> &gt; &amp; Infos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify if the intrinsic has variable arguments.</p>


<p>This method is intended to be called after all the fixed arguments have been matched first.</p>


<p>This method returns true on error.</p>


<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a> and <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#a4bdf4f1a432b628d6c78a4942244c0fca484f6ab5099f6776d80396a092c84ac5">llvm::Intrinsic::IITDescriptor::VarArg</a>.</p>


<p>Referenced by <a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a>.</p>

</div>
</div>

### remangleIntrinsicFunction() {#a3ce5fd3a8d74ecd38fdb5e27f85d2d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Function * &gt; llvm::Intrinsic::remangleIntrinsicFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>, definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="#adce8df27d44de3e02c13209348660f0e">getIntrinsicSignature</a>, <a href="#a7157f9fa9dd11f234ec3c58517cb6d96">getName</a>, <a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#ae6db8746934e6feae3649a8709fce3cc">llvm::Function::setCallingConv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### id {#a1fd225da5fcb670947a8e869fce8650e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ID llvm::Intrinsic::id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>Referenced by <a href="#aac36688686cd311fab09e6b55efb7f96">getBaseName</a>.</p>

</div>
</div>

### NoAliasScopeDeclScopeArg {#a93df8888c3b6eb4e7e5df51033799693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::Intrinsic::NoAliasScopeDeclScopeArg = 0</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a34f6aa565eff649a89e0406f516d12a5">llvm::NoAliasScopeDeclInst::getScopeList</a> and <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a2defed486cd9ee3d4ff214afbd0c9066">llvm::NoAliasScopeDeclInst::setScopeList</a>.</p>

</div>
</div>

### Tys {#a042f275033dbeb7761b82e5368e871bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ID ArrayRef&lt;Type *&gt; llvm::Intrinsic::Tys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {}) {
    return <a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a>(M, <a href="#a1fd225da5fcb670947a8e869fce8650e">id</a>, Tys);
  }
  <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *<a href="#aa1731508126b77035ab3ba9d71d5374b">getDeclarationIfExists</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *M, <a href="#a80add6b3b1cdaec560907995127adc16">ID</a> <a href="#a1fd225da5fcb670947a8e869fce8650e">id</a>)
</div>
</dd>
</dl>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a>.</p>


<p>Referenced by <a href="#a89cda2218259523c41863fc1175d6907">getAttributes</a>, <a href="#aa1731508126b77035ab3ba9d71d5374b">getDeclarationIfExists</a>, <a href="#a9a6d8be4a3793bd5cef4d3f25508a4fa">getName</a>, <a href="#a3b2b24ea2831ebf75ab12501d3ca89e8">getNameNoUnnamedTypes</a>, <a href="#a0cff8be0190d8e20b7cf13646f34afa2">getOrInsertDeclaration</a> and <a href="#aca1828635e30f34e4958afeb5541766e">getType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericssacontext-h">GenericSSAContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">Intrinsics.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
