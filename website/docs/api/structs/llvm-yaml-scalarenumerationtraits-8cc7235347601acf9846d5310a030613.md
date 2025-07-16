---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalarenumerationtraits-8cc7235347601acf9846d5310a030613
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarEnumerationTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarEnumerationTraits&lt;XCOFF::StorageClass&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">llvm/ObjectYAML/XCOFFYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d11985d2edf474752cdfc860322287">enumeration</a> (IO &amp;IO, XCOFF::StorageClass &amp;Value)</td>
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


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### enumeration() {#a92d11985d2edf474752cdfc860322287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::StorageClass &gt;::enumeration (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a> &amp; Value)</td>
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



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aa804b18d5bc65c8ff7f7487fffffd8a7">llvm::XCOFF::C_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a25d455ff3a664bef107d47221af3c6dc">llvm::XCOFF::C_ARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a44e2591f735b44c8efce8db2b3cd9e58">llvm::XCOFF::C_AUTO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a092dfc761b213557b52706a6832b9cc7">llvm::XCOFF::C_BCOMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a3808d2da54bf5b3f6f857accbe2c3880">llvm::XCOFF::C_BINCL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a66c2b93e45dc730a3b17051d5b2d6fd3">llvm::XCOFF::C_BLOCK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70afcfb22d749188fb257dac81a5048e61a">llvm::XCOFF::C_BSTAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a22f4ff6ef6a421521b45beaf03de6e65">llvm::XCOFF::C_DECL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ac93234a364235748b00c29e5b74fa37a">llvm::XCOFF::C_DWARF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ac2711eb069b88c200ab2ca3c68577be0">llvm::XCOFF::C_ECOML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70afafe0602b4d711b2fee4c6b610012def">llvm::XCOFF::C_ECOMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aa8cfad4a65a4c9f06d6eb235a8d9957b">llvm::XCOFF::C_EFCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a9a8191c757881847ba1f1023778377ee">llvm::XCOFF::C_EINCL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a9833a6c18e0c7b8c2b5ad51150f8c057">llvm::XCOFF::C_ENTAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a7bb74316ff9281462e80e36f26bcb6d9">llvm::XCOFF::C_ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a0f605fcb60753d7369dc31b4d5b98c95">llvm::XCOFF::C_EOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70affd823048db3a0e496e765d352446a5f">llvm::XCOFF::C_ESTAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261">llvm::XCOFF::C_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a4f655dd1f0a80bd6ad9af733c5fce458">llvm::XCOFF::C_EXTDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aa3af513e95c6ae116a7fda56503371e1">llvm::XCOFF::C_FCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a366cd9be1725b5f7a95799fd7f188e1e">llvm::XCOFF::C_FIELD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ab3ab2990d9bd88d3ff52e29f0ad776bf">llvm::XCOFF::C_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a21dd315e5812d908aad50ccf97c9f98d">llvm::XCOFF::C_FUN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a36ff92d88b07b2bd646659884e150690">llvm::XCOFF::C_GSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a1629ee4e5de0988849d22ed29070e966">llvm::XCOFF::C_GTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70adcc91f5755c6978ad8625a83adf87230">llvm::XCOFF::C_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24">llvm::XCOFF::C_HIDEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a6c5f18c2d2f8ef4554287499b92dc853">llvm::XCOFF::C_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a551d2c39eb0ac93c195e5f301b0908f4">llvm::XCOFF::C_LABEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a174eaaa6c9518e2eeae14ce0de973719">llvm::XCOFF::C_LINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a9d4afaff861a057bff2f7c5af08c32d7">llvm::XCOFF::C_LSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a0286450c0240ddf2918a0270eecd47d2">llvm::XCOFF::C_MOE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a59294c9167080d273884fda5b8565dbc">llvm::XCOFF::C_MOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ace13229751c9d27d68bf8ecd61cc816a">llvm::XCOFF::C_MOU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ac131afeee63f28c559e32b0ca3816a53">llvm::XCOFF::C_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a23b5d2359b6b02d84912cd103918eafe">llvm::XCOFF::C_PSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a619d9caa658508165d149f4e9de5ae60">llvm::XCOFF::C_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ae40e51a60986650c4c81d1de654139ef">llvm::XCOFF::C_REGPARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a2d836f8d2e1d3a5e027f17a61d1ff267">llvm::XCOFF::C_RPSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a4b786a64d1bbc3b454c56a1892a868b4">llvm::XCOFF::C_RSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a690257670e7c27f441d8f5d5508f8b61">llvm::XCOFF::C_STAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a2ff548e5bdf7ffa54c16a60d1b9a7c0c">llvm::XCOFF::C_STRTAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ac23cf4733be97ac47ac844fa6ae6dab8">llvm::XCOFF::C_STSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8047e38123f8e32b2417e57003021cfc">llvm::XCOFF::C_STTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70af0657d2e13ef79a76f35f40360bee91f">llvm::XCOFF::C_TCSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ae9c4390c7173df2cf0bc6dba3934ab03">llvm::XCOFF::C_TPDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ab25f119012e7012ef0ac4cceba4fda90">llvm::XCOFF::C_ULABEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a40d4ceefbe7e6f4ac3a277a326af1e44">llvm::XCOFF::C_UNTAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aedbae8ca40257b09c7cfdbc625ef1300">llvm::XCOFF::C_USTATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e">llvm::XCOFF::C_WEAKEXT</a> and <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/wasm-cpp/#a8c36a148929ce5ee501d6c5e99ed059b">ECase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
