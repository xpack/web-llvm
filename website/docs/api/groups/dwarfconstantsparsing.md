---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/dwarfconstantsparsing
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# Dwarf constants parsing functions

<p>These functions map their strings back to the corresponding enumeration value or return 0 if there is none, except for these exceptions: <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5e36554e194e99d7da32c35d16ba453a">getTag</a> (StringRef TagString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3282147626ca93f5875a224cf648aa94">getOperationEncoding</a> (StringRef OperationEncodingString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga183a5264c7ee13f65123fc83fb0c923c">getSubOperationEncoding</a> (unsigned OpEncoding, StringRef SubOperationEncodingString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga79029f75d17b7821fd61ec6b992d0f84">getVirtuality</a> (StringRef VirtualityString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga74b19c4e1fb8540a9975e774efc46fd9">getLanguage</a> (StringRef LanguageString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga70747367467013c5b906dd29773f16e0">getCallingConvention</a> (StringRef LanguageString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga42773bac5182a842f016704db8007e54">getAttributeEncoding</a> (StringRef EncodingString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaedfb90cbf93ba3782def5165b3830452">getMacinfo</a> (StringRef MacinfoString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae0b335b23d55246b9c836013516d92d5">getMacro</a> (StringRef MacroString)</td>
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

<p>These functions map their strings back to the corresponding enumeration value or return 0 if there is none, except for these exceptions:</p>


<ul class="doxyList ">
<li><em><a href="#ga5e36554e194e99d7da32c35d16ba453a">getTag()</a></em> returns <em>DW_TAG_invalid</em> on invalid input.</li>
<li><em><a href="#ga79029f75d17b7821fd61ec6b992d0f84">getVirtuality()</a></em> returns <em>DW_VIRTUALITY_invalid</em> on invalid input.</li>
<li><em><a href="#gaedfb90cbf93ba3782def5165b3830452">getMacinfo()</a></em> returns <em>DW_MACINFO_invalid</em> on invalid input.</li>
</ul>

<div class="doxySectionDef">

## Functions

### getAttributeEncoding() {#ga42773bac5182a842f016704db8007e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getAttributeEncoding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EncodingString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a056d8ee2e72bc9d8bc6fc68313378e23">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getCallingConvention() {#ga70747367467013c5b906dd29773f16e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getCallingConvention (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LanguageString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a345d7c4db2764f44efd8bf58770928d7">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getLanguage() {#ga74b19c4e1fb8540a9975e774efc46fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getLanguage (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LanguageString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga6040ef7c99341269e7c3ffe8347f72b3">llvm::dwarf::LanguageString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#adedf4778a9d218a587c1d18bf9e02474">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getMacinfo() {#gaedfb90cbf93ba3782def5165b3830452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getMacinfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MacinfoString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1aa2d5a6f618fb7bc61c2b48b6cbd6f605">llvm::dwarf::DW_MACINFO_define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a56df0efb5fc212b496310f6a3e3ae656">llvm::dwarf::DW_MACINFO_end_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a955ccfcc72dc8efd5d68f8ede36cb563">llvm::dwarf::DW_MACINFO_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a494aa8941672ece775a0e3996c43495c">llvm::dwarf::DW_MACINFO_start_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1a1d03dab779486bab7cfd80a9d1b15d16">llvm::dwarf::DW_MACINFO_undef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1aa8663792ff02d1695c013278102344ca">llvm::dwarf::DW_MACINFO_vendor_ext</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gad07ea9fcc31eab665ecf3004109a59bb">llvm::dwarf::MacinfoString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a089d6dfe66bd827e2bdad201383a5d63">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getMacro() {#gae0b335b23d55246b9c836013516d92d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MacroString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a955ccfcc72dc8efd5d68f8ede36cb563">llvm::dwarf::DW_MACINFO_invalid</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga54cd8f8c4d63e99a84c519ff889fc9db">llvm::dwarf::MacroString</a>.</p>

</div>
</div>

### getOperationEncoding() {#ga3282147626ca93f5875a224cf648aa94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getOperationEncoding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OperationEncodingString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca1d4cd3c9f41c395601558b0bec435888">llvm::dwarf::DW_OP_LLVM_implicit_pointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca989f426170b8ef321ffeb4838b4c590f">llvm::dwarf::DW_OP_LLVM_tag_offset</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gad20f8c5eb7af765400eea967ff2645b3">llvm::dwarf::OperationEncodingString</a>.</p>

</div>
</div>

### getSubOperationEncoding() {#ga183a5264c7ee13f65123fc83fb0c923c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getSubOperationEncoding (unsigned OpEncoding, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SubOperationEncodingString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp/#a4343b39231fb6db37ae8b55d21245386">getLlvmUserOperationEncoding</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga5f3afab9bb796a171a9433e9b8ccbfcd">llvm::dwarf::SubOperationEncodingString</a>.</p>

</div>
</div>

### getTag() {#ga5e36554e194e99d7da32c35d16ba453a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getTag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TagString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a64aca7a0743065ff63ca84cb013f08fd">llvm::dwarf::DW_TAG_invalid</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">llvm::DWARFUnit::getLastChildEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/llparser/#ab5ae8011166e33d1f6b5ea8847cb9329">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

### getVirtuality() {#ga79029f75d17b7821fd61ec6b992d0f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf::getVirtuality (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VirtualityString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4aace94a5cb6c3f6e98251b9257a5e7893">llvm::dwarf::DW_VIRTUALITY_invalid</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga71d4b95593d9e413728b7e126d995d89">llvm::dwarf::VirtualityString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/llparser/#a8b98975ff05abf17080af8cd0278a60e">llvm::LLParser::parseMDField</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
