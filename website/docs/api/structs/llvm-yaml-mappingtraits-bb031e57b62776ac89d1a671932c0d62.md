---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-bb031e57b62776ac89d1a671932c0d62
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;COFFYAML::PEHeader&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">llvm/ObjectYAML/COFFYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc106d67a20f42b39a79a6a9374ca89">mapping</a> (IO &amp;IO, COFFYAML::PEHeader &amp;PH)</td>
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


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#abcc106d67a20f42b39a79a6a9374ca89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; COFFYAML::PEHeader &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/peheader">COFFYAML::PEHeader</a> &amp; PH)</td>
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



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffyaml-cpp">COFFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a19b69395784388fe7c43dc21198841f2">llvm::COFF::PE32Header::AddressOfEntryPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a000e0e9b480a823b466ebabbb48c44dd">llvm::COFF::ARCHITECTURE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404acc4d781b52c2d72f802a73e2da6bc527">llvm::COFF::BASE_RELOCATION_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ae16fac3d25a807bbb32201c2bcd6feed">llvm::COFF::BOUND_IMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a0b437a9b662ed4445120d357e3bd7717">llvm::COFF::CERTIFICATE_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ab55f38b07dfadbac0606ae94e7411164">llvm::COFF::CLR_RUNTIME_HEADER</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/peheader/#a8855bb97167d140e4b0d1448199cf70a">llvm::COFFYAML::PEHeader::DataDirectories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ac180d06a50e9fc580140a835bb60fb8c">llvm::COFF::DEBUG_DIRECTORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a78b3b932a18d150c8bbd61c0b6387fa8">llvm::COFF::DELAY_IMPORT_DESCRIPTOR</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a9cde1f20e553ce0951022516a78ef894">llvm::COFF::PE32Header::DLLCharacteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a16cf92cd5538d6f55f3a823374689c1f">llvm::COFF::EXCEPTION_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a1ca50bd7c8aca4ffceffb0404f6d61fc">llvm::COFF::EXPORT_TABLE</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a363dbd69ead76c023c43b20e7b9a4bae">llvm::COFF::PE32Header::FileAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a1a57be485d7c9a9ed17b1c2940ef4576">llvm::COFF::GLOBAL_PTR</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/peheader/#ac51140c8cd6e11e7da26ed371b03abd5">llvm::COFFYAML::PEHeader::Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a09af83eabffcd3c2f3a4d535dfe21c7e">llvm::COFF::IAT</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a7d0a17e3f8c99741e8a12dc0b302497f">llvm::COFF::PE32Header::ImageBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a29a5bf8e7c9f7915eea435e7814880f9">llvm::COFF::IMPORT_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a26099233c856b980f1aab62126151a85">llvm::COFF::LOAD_CONFIG_TABLE</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#ac5f21edab3a6aa7c0efee13d1514904c">llvm::COFF::PE32Header::MajorImageVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a99a263f34a9c23ff9f940171a1b52939">llvm::COFF::PE32Header::MajorOperatingSystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a89ac92b5451a23de6e3e9603298949cd">llvm::COFF::PE32Header::MajorSubsystemVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a8d454220b5242e13bc8fe4d9c737918f">llvm::COFF::PE32Header::MinorImageVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a73d1aead73418d00f98b085ca0ff71d2">llvm::COFF::PE32Header::MinorOperatingSystemVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#ab2ce4fb372576e6f6f930ae1c206f12f">llvm::COFF::PE32Header::MinorSubsystemVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ad605c44010a7c6a6d92d03ab61779a14">llvm::COFF::NUM_DATA_DIRECTORIES</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#acf4e9d95dd52ac8ead1600cc54da2573">llvm::COFF::PE32Header::NumberOfRvaAndSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404ab906b768b4f9b4d6f5f83efa00ba7761">llvm::COFF::RESOURCE_TABLE</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#abe68d2183f33654e7bb2577e534a3129">llvm::COFF::PE32Header::SectionAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#af60a65683885d1855d42f3a0a1e77f90">llvm::COFF::PE32Header::SizeOfHeapCommit</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a6a05fbe19514f34cac4489347b32093d">llvm::COFF::PE32Header::SizeOfHeapReserve</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#a438323ac42adb461b6b13f89c4fb5d97">llvm::COFF::PE32Header::SizeOfStackCommit</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#aaf093d310542e51a596beb667520fb61">llvm::COFF::PE32Header::SizeOfStackReserve</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#ae5f22ab7d81ac3332e3440e6318b8ab9">llvm::COFF::PE32Header::Subsystem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a8ec28bc8cedea7febace40170acf2404a12d930221a4e7d4f2997348130a06919">llvm::COFF::TLS_TABLE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffyaml-cpp">COFFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
