---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/binaryformat/wasm-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Wasm.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">llvm/BinaryFormat/Wasm.h</a>"
#include "llvm/BinaryFormat/WasmRelocs.def"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105ee8fbb8d29d0ee933aa42d9c8ade0">WASM_RELOC</a>(NAME, VALUE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c36a148929ce5ee501d6c5e99ed059b">ECase</a>(X)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Macro Definitions

### ECase {#a8c36a148929ce5ee501d6c5e99ed059b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ECase(X)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case wasm::WASM_SEC_##X:                                                     \
    return #<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>;
</div>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/wasm-cpp">Wasm.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarbitsettraits-5fd0c59f5fca4e85d5ae4ba594ef2b3d/#a3528958420101c3f811341af85a9cdb0">llvm::yaml::ScalarBitSetTraits&lt; XCOFF::SectionTypeFlags &gt;::bitset</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-006575936be097bb885ff90c1dcd6e8a/#a60d7cb802008d8d4ea77b9681604095b">llvm::yaml::ScalarEnumerationTraits&lt; COFF::MachineTypes &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-407dfccc3a54e558cb6d2f0641260726/#ae3c0ce4b1d4b2c66209726c3137c3a46">llvm::yaml::ScalarEnumerationTraits&lt; COFF::RelocationTypeAMD64 &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-80ac6fb399619e44635431fc90c3b8e2/#aece6f69ae6e2995c37646d67e458e24f">llvm::yaml::ScalarEnumerationTraits&lt; COFF::RelocationTypeI386 &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-b23f7b3f29084f08500d9d8bef9cfb0d/#a1982103318c04376c67d4efb57c0a445">llvm::yaml::ScalarEnumerationTraits&lt; COFF::RelocationTypesARM &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-42cf97a13c3285028d12fa367baaf265/#a2d6a51f4041db4fd7c63c25a50253506">llvm::yaml::ScalarEnumerationTraits&lt; COFF::RelocationTypesARM64 &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-19005e0af95e4a1b514fef7e792ef3ca/#a7bb8c37d085c057993815b1a4f37c00c">llvm::yaml::ScalarEnumerationTraits&lt; COFF::RelocationTypesMips &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-36a80b6903185c75bdd91924e1c0821e/#a409c0684168311455c2221aecf3b98a6">llvm::yaml::ScalarEnumerationTraits&lt; COFF::SymbolBaseType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-702e46cd8859bdcfc006b352096660d7/#ae2aff4175fb866fd64d999297d919bd8">llvm::yaml::ScalarEnumerationTraits&lt; COFF::SymbolComplexType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-b4bc88540ccce709cb120b575aab5fb8/#a59423ae580ebc0479b6f59f02251fcb5">llvm::yaml::ScalarEnumerationTraits&lt; COFF::SymbolStorageClass &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-8dcb368b4bfc706aaf2e5b9d79dcea8b/#affa50d4c063d973dcd889f2f445f8460">llvm::yaml::ScalarEnumerationTraits&lt; COFF::WindowsSubsystem &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-4b3a928dbbaa0e1ae27f743a35f58bcc/#a1170f175de31392cde9eea0b4caf7f2f">llvm::yaml::ScalarEnumerationTraits&lt; COFFYAML::AuxSymbolType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-f153b28368f6ef8adf9af0478c703e5e/#a5ccd35b5b020b4c4a34623a2a5e59e57">llvm::yaml::ScalarEnumerationTraits&lt; COFFYAML::COMDATType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-563ea2a03de3562c3bbf4300620f3cb7/#a5bff560ce7d8158439fee24717b5393b">llvm::yaml::ScalarEnumerationTraits&lt; COFFYAML::WeakExternalCharacteristics &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-83c78b24ee4d0d13494c64d4d4cade21/#a5c9ec931b10650f5151ed4b47a18c7b9">llvm::yaml::ScalarEnumerationTraits&lt; object::ImageKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-52748f3f5fc9dcda07f1b515b337b87f/#aa0ce64bd19b2715b33951eaf75802bdd">llvm::yaml::ScalarEnumerationTraits&lt; object::OffloadKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-811ae43c28cafd3ad6d10512390e7b83/#a7ee6b18ce8af89b20d73a648baee5090">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ComdatKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-31797686350f02d80165f80902559b21/#ac5b8f6d035149c16326319fc0d5d3504">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ExportKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-06963dc1db55db23c3d9537dc5d4322a/#aadc58003efca3976d884f35fd23df322">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::FeaturePolicyPrefix &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-c62479be77e26ca8838d37deb22f5920/#ae37a9cfccf7e855988bba831cd761990">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::Opcode &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-4d3b57d02aa31561a81549422cec002a/#a0c1f18fc9fdd6562607eb852adf9aa9e">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::SectionType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-69628323fc5d4466075199eb0e0fa69d/#a70de3432b4436060c4192ad81a5df3db">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::SymbolKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-d53c04017074ad1bd3ff46f36bc5ca1a/#a968cc1b6ad3690fbc7176bbdbadf0573">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::TableType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-1c3bd737691f36eaba9501ef794ab207/#a7c4b27f07e30d8d62344fc85ab9bb714">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ValueType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-e48699e567747de9603c61d475bdb3ac/#a1a665f1dfb11b2a8933b1318b1e58156">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::CFileStringType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-f198651d9f0383590aef569382e0fdcb/#a4da318299c6766c9c7f2ee6210228361">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::DwarfSectionSubtypeFlags &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-8cc7235347601acf9846d5310a030613/#a92d11985d2edf474752cdfc860322287">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::StorageClass &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-d893dcf7bebdaa281a0012a1b110b432/#a381e3e8134b156207b36e4b51d5ca157">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::StorageMappingClass &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-50ae04bf469790ba6dee903817607680/#a3e1f63d55dda4d3b4c1eac2678c7e4a3">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::SymbolType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-a660d6b1d3cff609101ae359df061565/#a73b78838d24b6c9820c83e5465caf702">llvm::yaml::ScalarEnumerationTraits&lt; XCOFFYAML::AuxSymbolType &gt;::enumeration</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ac737e1f79f17b2a3b9abb858d18257cc">llvm::wasm::sectionTypeToString</a>.</p>

</div>
</div>

### WASM\_RELOC {#a105ee8fbb8d29d0ee933aa42d9c8ade0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define WASM_RELOC(NAME, VALUE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case VALUE:                                                                  \
    return #NAME;
</div>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/wasm-cpp">Wasm.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
