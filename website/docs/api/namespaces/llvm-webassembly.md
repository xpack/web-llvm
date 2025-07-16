---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/webassembly
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `WebAssembly` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::WebAssembly { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassembly/sortregion">SortRegion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassembly/concretesortregion">ConcreteSortRegion&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassembly/sortregioninfo">SortRegionInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Tag { <a href="#a2ce2d5b62438d2fa7d7cb37d232f52a1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#aa08825e8a9ab12c1a9fa8e52f02718e0">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType { <a href="#aa5fb9c8405de3efed868f5de2d0ed4e8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BlockType : unsigned { <a href="#a9ebf832762357f1668dbc7fd07668de4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used as immediate MachineOperands for block signatures. <a href="#a9ebf832762357f1668dbc7fd07668de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WasmAddressSpace : unsigned { <a href="#a4dfe79d002517ae351f8af2245726c78">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetIndex { <a href="#afb0e38d707f5f5ed287dd43193a61f3c">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6729ecc49fdb9bc1e01cb9e6f8a64b7">GetDefaultP2AlignAny</a> (unsigned Opc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the default p2align value for a load or store with the given opcode. <a href="#aa6729ecc49fdb9bc1e01cb9e6f8a64b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a5d29a901287f6b88bf88e4d812f625">GetDefaultP2Align</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96aa429fc26326800379bb06512648ac">isConst</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31ca7d5649f6d16c56eba98634d60f2">isScalarConst</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15296a1aa48a333f25583e31fd8f2a40">isArgument</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850b55e79066ad88588cfb6b740f8655">isCopy</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd4c79cd9af314c5d43043e10dcb0db">isTee</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac361b53d0a877031bfd4b8b4e52b853f">isCallDirect</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f95094c89d3bf2738057a3278bf6b4">isCallIndirect</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f816bb54827dac93c4d2c64ecad7878">isBrTable</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3982a1bf74ed2e218a45c7894fc660ac">isMarker</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d6a3f5d24c97c850346915bc114e4b1">isEndMarker</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f9d59e0218f930dedb4725b6df7371">isTry</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e775f5df24e1c131a9e1840877503ce">isCatch</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7b0bfa782962c21346bf0c7f463d60">isCatchAll</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b0f07eeb2793f36db70e3a80b736df">isLocalGet</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae107f1555331a3422b7fbfe1b85d82dc">isLocalSet</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1124cde121d57efe04ea42bc165eb583">isLocalTee</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3603fdd430b146d72370dd19afa46d6">getWARegStackId</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cf3dad6e6b882d8cbf39de2ded9558">isRefType</a> (wasm::ValType Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4634f1f44bd5719bcbc73540b0e23e5">anyTypeToString</a> (unsigned Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11bf36ed68b39005def2a7105a789863">typeToString</a> (wasm::ValType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace38cf69cdffc766897324c5c07e6007">typeListToString</a> (ArrayRef&lt; wasm::ValType &gt; List)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab777621cd8cd052180667366c7191456">signatureToString</a> (const wasm::WasmSignature *Sig)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af26fa5743569531580fe2e12eb594d">regClassToValType</a> (unsigned RC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55eace303da656ab895760ed2f6da26">parseType</a> (StringRef Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9ebf832762357f1668dbc7fd07668de4">BlockType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36696bf11093560ddae04b19b3e6857a">parseBlockType</a> (StringRef Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee7a1febd29dce54c5499c54e7f5f980">getStackOpcode</a> (unsigned short Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826d606941b4ed839b011ecbb16e2468">getRegisterOpcode</a> (unsigned short Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076d4939d577df2c4f5ddbb3bb807f56">getWasm64Opcode</a> (unsigned short Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4dff4ccfc2539f59ef6bd15dc5e629">isDefaultAddressSpace</a> (unsigned AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45a1b676eb96b330c6a5bb5dab029ae">isWasmVarAddressSpace</a> (unsigned AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eacdd4ec3308700b0783d15978f9e54">isValidAddressSpace</a> (unsigned AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9e7ebbbd5f298ad775c53afeff637c">isWebAssemblyExternrefType</a> (const Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Externref <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a1a9e7ebbbd5f298ad775c53afeff637c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de30f2c5dd4809d2b8261f23e8d7e6e">isWebAssemblyFuncrefType</a> (const Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Funcref <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a5de30f2c5dd4809d2b8261f23e8d7e6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be40d1caf33e1e14d176d2a714b760c">isWebAssemblyReferenceType</a> (const Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Reference <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a6be40d1caf33e1e14d176d2a714b760c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6edd1388aabcf34144b4bbbea08ee00d">isWebAssemblyTableType</a> (const Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the table represents a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> table type. <a href="#a6edd1388aabcf34144b4bbbea08ee00d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad633bade17028bdef34a0637c012eeb2">parseMVT</a> (StringRef Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623013f677a44a584a4fad200887a4a0">toValType</a> (MVT Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711350a8af2fb95f4f1ca8cb7fa79374">wasmSymbolSetType</a> (MCSymbolWasm *Sym, const Type *GlobalVT, ArrayRef&lt; MVT &gt; VTs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets a Wasm Symbol <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a711350a8af2fb95f4f1ca8cb7fa79374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb084ddbc36c852ebf26086505e9def6">getNamedOperandIdx</a> (uint16_t Opcode, uint16_t NamedIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8304b7081ccb7ef24cae34433ce796f1">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94b800d0b8c1e3423be89c87d447c9c">getLibcallSignature</a> (const WebAssemblySubtarget &amp;Subtarget, RTLIB::Libcall LC, SmallVectorImpl&lt; wasm::ValType &gt; &amp;Rets, SmallVectorImpl&lt; wasm::ValType &gt; &amp;Params)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d7f8be38fb2af6b7db48815f3b9e0a">getLibcallSignature</a> (const WebAssemblySubtarget &amp;Subtarget, StringRef Name, SmallVectorImpl&lt; wasm::ValType &gt; &amp;Rets, SmallVectorImpl&lt; wasm::ValType &gt; &amp;Params)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1403d0f29e96c05811fe277c8c68eae6">isChild</a> (const MachineInstr &amp;MI, const WebAssemblyFunctionInfo &amp;MFI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether MI is a child of some other node in an expression tree. <a href="#a1403d0f29e96c05811fe277c8c68eae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59640be12351dbd3b6a2914e5ab386a7">getCalleeOp</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the operand number of a callee, assuming the argument is a call instruction. <a href="#a59640be12351dbd3b6a2914e5ab386a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33df8ca13cb8bb9e37d1f43b202aef7f">getOrCreateFunctionTableSymbol</a> (MCContext &amp;Ctx, const WebAssemblySubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the __indirect_function_table, for use in call_indirect and in function bitcasts. <a href="#a33df8ca13cb8bb9e37d1f43b202aef7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7258bffac41959b91226f473086e93a2">getOrCreateFuncrefCallTableSymbol</a> (MCContext &amp;Ctx, const WebAssemblySubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the __funcref_call_table, for use in funcref calls when lowered to table.set + call_indirect. <a href="#a7258bffac41959b91226f473086e93a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc6351696a872f05cdf540a663d584c">findCatch</a> (MachineBasicBlock *EHPad)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a catch instruction from an EH pad. <a href="#a6cc6351696a872f05cdf540a663d584c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401b0a43069b4766865e9e83de7deb16">getCopyOpcodeForRegClass</a> (const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the appropriate copy opcode for the given register class. <a href="#a401b0a43069b4766865e9e83de7deb16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227338989166dc1f17719c1e241e9376">canLowerMultivalueReturn</a> (const WebAssemblySubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if multivalue returns of a function can be lowered directly, i.e., not indirectly via a pointer parameter that points to the value in memory. <a href="#a227338989166dc1f17719c1e241e9376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9608d0a61030f1d1159ebdac22ba6ddc">canLowerReturn</a> (size_t ResultSize, const WebAssemblySubtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function's return value(s) can be lowered directly, i.e., not indirectly via a pointer parameter that points to the value in memory. <a href="#a9608d0a61030f1d1159ebdac22ba6ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d507b0cb1cf288e6fe831666a8b8668">WasmEnableEmEH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab16d00c5762ae8f5a89ce045b44b07e">WasmEnableEmSjLj</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d68f56b86e580ac9d156b47af53c2c">WasmEnableEH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877b8fcf196f226d4f2289ebdb1f276b">WasmEnableSjLj</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b0b93d22f984ea3f11e3fc04dbe744">WasmUseLegacyEH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8252c3c3e2c889ea98eea628b81d2999">Nop</a> = 0x01</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> opcodes emitted via means other than CodeGen. <a href="#a8252c3c3e2c889ea98eea628b81d2999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905cd49db07f7404b218ee58818c80a9">End</a> = 0x0b</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77bfe2fcd74307eb34fab682645aea2a">UnusedReg</a> = -1u</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8421ef1abb7fb4c5c61d8954924c35">ClangCallTerminateFn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05fda0e278d12242b0e6026ec6b23643">CxaBeginCatchFn</a> = "__cxa_begin_catch"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e7caa6d9b0e8793080c9af8f8a3441">CxaRethrowFn</a> = "__cxa_rethrow"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01758e2eef813342e32cce438ce1af58">StdTerminateFn</a> = "_ZSt9terminatev"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905f7fa7e3adde06b01c794635b5c8a5">PersonalityWrapperFn</a> = ...</td>
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

## Enumerations

### BlockType {#a9ebf832762357f1668dbc7fd07668de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::WebAssembly::BlockType : unsigned</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used as immediate MachineOperands for block signatures.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a9ebf832762357f1668dbc7fd07668de4a4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Void<a id="a9ebf832762357f1668dbc7fd07668de4a81ceb48a978444906d80119200aa358d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I32<a id="a9ebf832762357f1668dbc7fd07668de4ad878ea6016bfe01729548bf442de5a8b"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::I32))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I64<a id="a9ebf832762357f1668dbc7fd07668de4ae7e62f6928f76df671b5a0379793fab6"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::I64))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F32<a id="a9ebf832762357f1668dbc7fd07668de4a44ad4ef5a76e6aa6fb3e3fa079a54fda"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::F32))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F64<a id="a9ebf832762357f1668dbc7fd07668de4a1ad5f6f3069070ec4cbbdc94d5e61e0e"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::F64))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V128<a id="a9ebf832762357f1668dbc7fd07668de4ac6e36782efab8dde234ebf42882bcd55"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::V128))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Externref<a id="a9ebf832762357f1668dbc7fd07668de4acfebcdb871bec28e8e49332e4c71c578"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::EXTERNREF))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Funcref<a id="a9ebf832762357f1668dbc7fd07668de4a2d7df65515abbb3ea6189c510ecbaaac"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::FUNCREF))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exnref<a id="a9ebf832762357f1668dbc7fd07668de4a81eac01ea412ff384d2b5cb3cc8ebc0a"></a></td>
<td class="doxyEnumItemDescription"> (= unsigned(wasm::ValType::EXNREF))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Multivalue<a id="a9ebf832762357f1668dbc7fd07668de4a934729080de1f9b454fd9776c7711c82"></a></td>
<td class="doxyEnumItemDescription"> (= 0xffff)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>.</p>

</div>
</div>

### Fixups {#aa08825e8a9ab12c1a9fa8e52f02718e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WebAssembly::Fixups </td>
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
<td class="doxyEnumItemName">fixup_sleb128_i32<a id="aa08825e8a9ab12c1a9fa8e52f02718e0a368f8bfe0cd2aac109aa698ec6b78379"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sleb128_i64<a id="aa08825e8a9ab12c1a9fa8e52f02718e0a228d68180745c8d6dcaf4eba597d1479"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_uleb128_i32<a id="aa08825e8a9ab12c1a9fa8e52f02718e0ad9ca950f4d8fba351134fb0de818551c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_uleb128_i64<a id="aa08825e8a9ab12c1a9fa8e52f02718e0a2c7af664640e2b0aa2e518861223fe59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="aa08825e8a9ab12c1a9fa8e52f02718e0a96b38ed2df1b6a32f7897b903e051a1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="aa08825e8a9ab12c1a9fa8e52f02718e0a54635a7cb0aefe8ca049aa8c4505cb68"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyfixupkinds-h">WebAssemblyFixupKinds.h</a>.</p>

</div>
</div>

### OperandType {#aa5fb9c8405de3efed868f5de2d0ed4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WebAssembly::OperandType </td>
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
<td class="doxyEnumItemName">OPERAND_BASIC_BLOCK<a id="aa5fb9c8405de3efed868f5de2d0ed4e8aabb0167f60f922020b8ebcea60c4c735"></a></td>
<td class="doxyEnumItemDescription">Basic block label in a branch construct (= MCOI::OPERAND_FIRST_TARGET)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_LOCAL<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a63411026264f0a1294c4f60ae6fb20fa"></a></td>
<td class="doxyEnumItemDescription">Local index</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_GLOBAL<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a09f453e3d5fdf684481c3c6dc28b87c9"></a></td>
<td class="doxyEnumItemDescription">Global index</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_I32IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a4ebc4195008f7f3bf8ddd489fa05eec6"></a></td>
<td class="doxyEnumItemDescription">32-bit integer immediates</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_I64IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8aea17c7ffb5a3fef3f0915ae981db449e"></a></td>
<td class="doxyEnumItemDescription">64-bit integer immediates</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_F32IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8aa717e539011be0292e3f1bba566c08c5"></a></td>
<td class="doxyEnumItemDescription">32-bit floating-point immediates</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_F64IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8abbe6aab8af6bfa7d451bb78452c9c95d"></a></td>
<td class="doxyEnumItemDescription">64-bit floating-point immediates</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_I8IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8ad3ac1c7f7ac238afd3a40af6006f65b9"></a></td>
<td class="doxyEnumItemDescription">8-bit vector lane immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_I16IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a6d919bf35a13262149ac61fcddb4fd6f"></a></td>
<td class="doxyEnumItemDescription">16-bit vector lane immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_I32IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8aaedb50f2eb3142d8d668276051bb820e"></a></td>
<td class="doxyEnumItemDescription">32-bit vector lane immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_I64IMM<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a6a3158a087be824cb85b5ef96b5269a9"></a></td>
<td class="doxyEnumItemDescription">64-bit vector lane immediate</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FUNCTION32<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a97238ec175415c150edd83ada138c34d"></a></td>
<td class="doxyEnumItemDescription">32-bit unsigned function indices</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_OFFSET32<a id="aa5fb9c8405de3efed868f5de2d0ed4e8af2cfe321188f43b34e71fe0a946236d5"></a></td>
<td class="doxyEnumItemDescription">32-bit unsigned memory offsets</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_OFFSET64<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a3e58c736aac1c4d4eec9d934a5a0c9d3"></a></td>
<td class="doxyEnumItemDescription">64-bit unsigned memory offsets</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_P2ALIGN<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a4f1b1da70524bd210612cfff4dba4834"></a></td>
<td class="doxyEnumItemDescription">p2align immediate for load and store address alignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIGNATURE<a id="aa5fb9c8405de3efed868f5de2d0ed4e8ae6c061da8f6273a4b534c59bdee5f385"></a></td>
<td class="doxyEnumItemDescription">signature immediate for block/loop</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_TYPEINDEX<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a77032abab1be768ed8eb86737d8a9bf2"></a></td>
<td class="doxyEnumItemDescription">type signature immediate for call_indirect</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_TAG<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a95cd6b67ece1e23cfe2ae3450841fff7"></a></td>
<td class="doxyEnumItemDescription"><a href="#a2ce2d5b62438d2fa7d7cb37d232f52a1">Tag</a> index</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_BRLIST<a id="aa5fb9c8405de3efed868f5de2d0ed4e8abbe654ed44ebe94527f6975c538c507f"></a></td>
<td class="doxyEnumItemDescription">A list of branch targets for br_list</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_TABLE<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a5f43782ba8195cd6112213ec19776bb3"></a></td>
<td class="doxyEnumItemDescription">32-bit unsigned table number</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_CATCH_LIST<a id="aa5fb9c8405de3efed868f5de2d0ed4e8a0dc3d6fc24502ff475ea07c3fdf05c34"></a></td>
<td class="doxyEnumItemDescription">A list of catch clauses for try_table</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### Tag {#a2ce2d5b62438d2fa7d7cb37d232f52a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WebAssembly::Tag </td>
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
<td class="doxyEnumItemName">CPP_EXCEPTION<a id="a2ce2d5b62438d2fa7d7cb37d232f52a1a2b2205e0ce930f6066cb652f7d17709e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">C_LONGJMP<a id="a2ce2d5b62438d2fa7d7cb37d232f52a1a9401129ec84978eddfb390a99db7adf9"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/wasmehfuncinfo-h">WasmEHFuncInfo.h</a>.</p>

</div>
</div>

### TargetIndex {#afb0e38d707f5f5ed287dd43193a61f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WebAssembly::TargetIndex </td>
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
<td class="doxyEnumItemName">TI_LOCAL<a id="afb0e38d707f5f5ed287dd43193a61f3cabc43eac6d18b7525076da25407e68d5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TI_GLOBAL_FIXED<a id="afb0e38d707f5f5ed287dd43193a61f3ca2d52830bb5a863f3eb7156340b130385"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TI_OPERAND_STACK<a id="afb0e38d707f5f5ed287dd43193a61f3ca39cac954a2f5be24ea149e76e935355b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TI_GLOBAL_RELOC<a id="afb0e38d707f5f5ed287dd43193a61f3ca11eb2918319786f66ec3b4d8f26dc1c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TI_LOCAL_INDIRECT<a id="afb0e38d707f5f5ed287dd43193a61f3ca9f9eae3ba2af23a2a920724d5642a42f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassembly-h">WebAssembly.h</a>.</p>

</div>
</div>

### WasmAddressSpace {#a4dfe79d002517ae351f8af2245726c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WebAssembly::WasmAddressSpace : unsigned</td>
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
<td class="doxyEnumItemName">WASM_ADDRESS_SPACE_DEFAULT<a id="a4dfe79d002517ae351f8af2245726c78a28b2cdf56b37b7d93db4aa3850682dd1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_ADDRESS_SPACE_VAR<a id="a4dfe79d002517ae351f8af2245726c78ad65bc6cefc871511e30423f55a1a4148"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_ADDRESS_SPACE_EXTERNREF<a id="a4dfe79d002517ae351f8af2245726c78a163c951c2848a11c33a29027580276c5"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WASM_ADDRESS_SPACE_FUNCREF<a id="a4dfe79d002517ae351f8af2245726c78af415dccc1391c50d45ec321f55292939"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/wasmaddressspaces-h">WasmAddressSpaces.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### anyTypeToString() {#ac4634f1f44bd5719bcbc73540b0e23e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::WebAssembly::anyTypeToString (unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eafa2c550d2128cc812bf5c320539bfc87">llvm::wasm::WASM_TYPE_EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea8fe9c097be76685c503bf24177988a49">llvm::wasm::WASM_TYPE_EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eae88d0b78646db504ac64a9b0245fb2ff">llvm::wasm::WASM_TYPE_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea3e127f09d14b44569016ccb43c255081">llvm::wasm::WASM_TYPE_F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea9ba342e672295a7d21e9c2fc89a1e262">llvm::wasm::WASM_TYPE_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea65b99d81eaf83487037a4d507a6f37a2">llvm::wasm::WASM_TYPE_FUNCREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eabde54aa45b9d6b85fb4c37fc5cca29f5">llvm::wasm::WASM_TYPE_I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea2b4b3bdb67bcba743db32a1c0684ccff">llvm::wasm::WASM_TYPE_I64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eac482647ad210ef3999a254f5a3e8b10b">llvm::wasm::WASM_TYPE_NORESULT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eaec7a320b098d9d72bb306fc75ab85646">llvm::wasm::WASM_TYPE_V128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a1e65050ef81c565f23ba4028e368c5fc">llvm::WebAssemblyInstPrinter::printWebAssemblySignatureOperand</a> and <a href="#a11bf36ed68b39005def2a7105a789863">typeToString</a>.</p>

</div>
</div>

### canLowerMultivalueReturn() {#a227338989166dc1f17719c1e241e9376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::canLowerMultivalueReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if multivalue returns of a function can be lowered directly, i.e., not indirectly via a pointer parameter that points to the value in memory.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a4ab35dc0ae65596d355bb98669e37a46">llvm::WebAssemblySubtarget::getTargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a7eb395364f9e0b23212f89fbe2b24269">llvm::WebAssemblySubtarget::hasMultivalue</a>.</p>


<p>Referenced by <a href="#a9608d0a61030f1d1159ebdac22ba6ddc">canLowerReturn</a> and <a href="#ae94b800d0b8c1e3423be89c87d447c9c">getLibcallSignature</a>.</p>

</div>
</div>

### canLowerReturn() {#a9608d0a61030f1d1159ebdac22ba6ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::canLowerReturn (size_t ResultSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the function's return value(s) can be lowered directly, i.e., not indirectly via a pointer parameter that points to the value in memory.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>Reference <a href="#a227338989166dc1f17719c1e241e9376">canLowerMultivalueReturn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>.</p>

</div>
</div>

### createFastISel() {#a8304b7081ccb7ef24cae34433ce796f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * llvm::WebAssembly::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-h">WebAssemblyISelLowering.h</a>, definition at line 1448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfastisel-cpp">WebAssemblyFastISel.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#a6e71c29d48aa6b75ec5a0ab52b28e67d">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::WebAssemblyFastISel</a>.</p>

</div>
</div>

### findCatch() {#a6cc6351696a872f05cdf540a663d584c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::WebAssembly::findCatch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * EHPad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a catch instruction from an EH pad.</p>


<p>Returns null if no catch instruction found or the catch is in an invalid location.</p>


<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="#a6e775f5df24e1c131a9e1840877503ce">isCatch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1100bfbadd996d464150c6a68fa8dc1d">llvm::MachineBasicBlock::isEHPad</a> and <a href="#a3982a1bf74ed2e218a45c7894fc660ac">isMarker</a>.</p>

</div>
</div>

### getCalleeOp() {#a59640be12351dbd3b6a2914e5ab386a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::WebAssembly::getCalleeOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the operand number of a callee, assuming the argument is a call instruction.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a363d901094623ef2445f8856ef1298e9">llvm::WebAssemblyInstrInfo::getCalleeOperand</a>, <a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ae9e91530b7f4d99adc7f3f43b35a00b9">queryCallee</a>.</p>

</div>
</div>

### getCopyOpcodeForRegClass() {#a401b0a43069b4766865e9e83de7deb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WebAssembly::getCopyOpcodeForRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the appropriate copy opcode for the given register class.</p>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a9eb8b24be429abb7d52e2f41f9923e08">llvm::WebAssemblyInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblypeephole-cpp/#aa0674cf65bb72bf5302d03cd85c3f14b">maybeRewriteToFallthrough</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a598eeebd324ee0050cc856e6e28f4778">unstackifyVRegsUsedInSplitBB</a>.</p>

</div>
</div>

### GetDefaultP2Align() {#a2a5d29a901287f6b88bf88e4d812f625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WebAssembly::GetDefaultP2Align (unsigned Opc)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>References <a href="#aa6729ecc49fdb9bc1e01cb9e6f8a64b7">GetDefaultP2AlignAny</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#ad73b288f9c90f95eec52c24cc346b69b">llvm::WebAssemblyInstPrinter::printWebAssemblyP2AlignOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblysetp2alignoperands-cpp/#a863a657b356a9f8556dcf310afe02c00">rewriteP2Align</a>.</p>

</div>
</div>

### GetDefaultP2AlignAny() {#aa6729ecc49fdb9bc1e01cb9e6f8a64b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WebAssembly::GetDefaultP2AlignAny (unsigned Opc)</td>
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

<p>Return the default p2align value for a load or store with the given opcode.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h/#aa323af52a93fc1b39a9fb67b7cc3d56f">WASM_LOAD_STORE</a>.</p>


<p>Referenced by <a href="#a2a5d29a901287f6b88bf88e4d812f625">GetDefaultP2Align</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### getLibcallSignature() {#ae94b800d0b8c1e3423be89c87d447c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::WebAssembly::getLibcallSignature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> LC, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt; &amp; Rets, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt; &amp; Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-h">WebAssemblyRuntimeLibcallSignatures.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-cpp">WebAssemblyRuntimeLibcallSignatures.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a227338989166dc1f17719c1e241e9376">canLowerMultivalueReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::wasm::F32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a49b3793ff14fea20ac45b87fc5f93ec9">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a6bc40fcb87d82c4dca3c7d2bc973f144">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_f32_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a788666e047a7434669abf7c2546ad6d2">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_f32_f32_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2adbdb5994e3c6a7594fe75c75cedad40e">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_f32_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a344be73374dc7bd2469147442a01c39d">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a6759581c700bfc70747db8909763c5e4">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_i16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a6e128f04add73ae01e231294c3743972">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a3647baf8707bac427b56d8386cf3e9b5">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a55f8fa69177a231cf90ad9c664bee6a2">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f32_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::wasm::F64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a1e99022a264cee288908b04c51718dd1">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2aba39bebe780b279f46d1ca89f6e8928f">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a639d80b654d41bb068812e5e23c47557">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_f64_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ab752d40394ed704af4a37ff9e2d8c2a6">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_f64_f64_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ae9fdbbe27ea608802abeab1e03856229">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_f64_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a748dc3e460822894c41e4178e4234419">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ab4d51fbfdbdb3eb235308298e26193f7">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2abcd8b097a3d1cbd7400438cdd0338b12">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::f64_func_i64_i64</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a55dce45877a3475cd98c9140a1bef4d7">func</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a0f78abe2fbacbdd56f37a4cd4716341d">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::func_f32_iPTR_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a1ea5160db9c08f7b6a0a0d374f65e07e">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::func_f64_iPTR_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2aa56bafd6e3e16d3a1a95522e02dd58cd">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::func_i64_i64_iPTR_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a38c60126950ce37348e16065c2929aa8">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::getRuntimeLibcallSignatures</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a5d7266cdd3774e32391b41afbf1eecde">llvm::WebAssemblySubtarget::hasAddr64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a544ba4a63d58eb6a84106d47b942357f">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i16_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2aba63aac52df22e3ef4760b59fa0a8022">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i16_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a844738787690e437598d4ce69fa668f6">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i16_func_i16_i16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2abd9e78ca73c39b342c1ca631191704bc">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i16_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2afd21ede0a9f51e0f22d5a157c1b2d6e4">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i16_i16_func_i16_i16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ad878ea6016bfe01729548bf442de5a8b">llvm::wasm::I32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2af3ca35fe46d3c1e3fd5553c577f6ce11">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a92e06fb53fe8837f51bce542e11a7c6e">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_f32_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a8c734c58b7b3c711f4f404bfb5617042">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a3fb0b589299a98b32359d724b7dd62a4">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_f64_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a42f5d8cf21c7ec934a39cf3136206948">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2aa24d6aad3085bab5572804c627e65760">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_i32_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac05980b99bbcd854c8f8c45728fbef7a">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_i32_i32_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a8d17d44bb5d33e119e319cb13df88f8c">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2afe0dfa43081723198b604d04e1771fb5">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_func_i64_i64_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac746012b46851d9edc03010f7c08142d">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i32_i32_func_i32_i32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ae7e62f6928f76df671b5a0379793fab6">llvm::wasm::I64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a600923f0d7c29388fe70168bab66110a">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2aa490a43f4573ce284365c7432bb175d4">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac5cc9d1ccaf374565dd452637a2bbfdf">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_func_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ad598054644aa13ae6c52a15eabb5b57b">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a7814955e73ccf85c021bd7188af54167">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_func_i64_i64_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a6bc198f6055f3fb8f75963a6aadbb02a">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a4b8b880ca531823a0ebff517a2f5fa5d">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a4cb803c6563c36b1be89b0f8e1282646">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2afeffedb23147b979ae8c39f96f888cd6">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ade6be5896e997ced5d30bcfe8b107cd5">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac1fd1c488cb2b30ec14115b459deb741">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64_i64_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac2a37d3e4ba68aac3168d240227491d1">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64_i64_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a548e4d02485362ab35e609e0c7784a91">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64_i64_i64_i64_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a8dadc00c5cd8a4a28bec7098d11c7d95">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_func_i64_i64_i64_i64_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a10b78d9b3094f93319398d96eb6ff563">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i64_i64_i64_i64_func_i64_i64_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a024a69a32a0c167ef6ee543e52074929">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::i8_func_i8_i8</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a584eb8d42862cc2f93c86455849e1be8">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_f32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a0a9e4cb9020f92a3d6d0dbcbc442f48d">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_f64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2acdd7dc758ee7126cd9306d816bf206f3">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_i32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ab99141da33a653aab7a3962221d67d86">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_i64_i64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2ac4decc8ec258cf7be1abb7eac794db1b">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_iPTR_i32_iPTR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyruntimelibcallsignatures-cpp-/#a6e5d41d50ab128ffcb71e02ab666fbf2a07372d2c38d58f6c54bb46490c9a4814">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::iPTR_func_iPTR_iPTR_iPTR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyruntimelibcallsignatures-cpp-/runtimelibcallsignaturetable/#ada7f835b1ccecc6dfa1e26d4a02fd071">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::RuntimeLibcallSignatureTable::Table</a> and <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp/#a1a923abcc65272bfe81c0e7081c32421">unsupported</a>.</p>


<p>Referenced by <a href="#aa0d7f8be38fb2af6b7db48815f3b9e0a">getLibcallSignature</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4d95a71faaca9c18ee44f1942b77c716">llvm::WebAssemblyAsmPrinter::getOrCreateWasmSymbol</a>.</p>

</div>
</div>

### getLibcallSignature() {#aa0d7f8be38fb2af6b7db48815f3b9e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::WebAssembly::getLibcallSignature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt; &amp; Rets, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt; &amp; Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-h">WebAssemblyRuntimeLibcallSignatures.h</a>, definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-cpp">WebAssemblyRuntimeLibcallSignatures.cpp</a>.</p>


<p>References <a href="#ae94b800d0b8c1e3423be89c87d447c9c">getLibcallSignature</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/anonymous-webassemblyruntimelibcallsignatures-cpp-/staticlibcallnamemap/#a87f55405733b732824da04aa468297f0">anonymous{WebAssemblyRuntimeLibcallSignatures.cpp}::StaticLibcallNameMap::StaticLibcallNameMap</a>.</p>

</div>
</div>

### getNamedOperandIdx() {#acb084ddbc36c852ebf26086505e9def6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t llvm::WebAssembly::getNamedOperandIdx (uint16_t Opcode, uint16_t NamedIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyinstrinfo-h">WebAssemblyInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#aa0150e2afe7a04001d1bbfc2ea7f4e76">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::runOnMachineFunction</a>.</p>

</div>
</div>

### getOrCreateFuncrefCallTableSymbol() {#a7258bffac41959b91226f473086e93a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolWasm * llvm::WebAssembly::getOrCreateFuncrefCallTableSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the __funcref_call_table, for use in funcref calls when lowered to table.set + call_indirect.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a0499b83dc894ada1126e6e791157980b">llvm::WebAssemblySubtarget::hasCallIndirectOverlong</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a5a2f276f396875ef912e9b13ba292663">llvm::MCSymbolWasm::isFunctionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a9b68f461b38d0ad3f9ff58f93e248de1">llvm::MCSymbolWasm::setOmitFromLinkingSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a044b57ea7f09bf315fe429350de59d25">llvm::MCSymbolWasm::setTableType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a817a67945b1632513e9b43ca0da9aacd">llvm::MCSymbolWasm::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a7e5b64abdda5a509f48743e420f4acb5">llvm::MCSymbolWasm::setWeak</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>.</p>

</div>
</div>

### getOrCreateFunctionTableSymbol() {#a33df8ca13cb8bb9e37d1f43b202aef7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolWasm * llvm::WebAssembly::getOrCreateFunctionTableSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> * Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the __indirect_function_table, for use in call_indirect and in function bitcasts.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a35b2acdbcca0a7fb18fc6474b2f2f61f">llvm::WebAssemblySubtarget::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a0499b83dc894ada1126e6e791157980b">llvm::WebAssemblySubtarget::hasCallIndirectOverlong</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9e0d7431e635bbbf753602d214d89f0e">llvm::Triple::isArch64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a5a2f276f396875ef912e9b13ba292663">llvm::MCSymbolWasm::isFunctionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a54d32c6868ad27b8c94d4d0e7134af2a">llvm::MCSymbolWasm::setFunctionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a9b68f461b38d0ad3f9ff58f93e248de1">llvm::MCSymbolWasm::setOmitFromLinkingSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab65fa2b7850f38cafbc74ab99c3a3fed">llvm::MCSymbol::setUndefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#af0cbac92300c3074e6bb81d58e92a86b">llvm::WebAssemblyAsmPrinter::emitEndOfAsmFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>.</p>

</div>
</div>

### getRegisterOpcode() {#a826d606941b4ed839b011ecbb16e2468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::WebAssembly::getRegisterOpcode (unsigned short Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-h">WebAssemblyTargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a>.</p>

</div>
</div>

### getStackOpcode() {#aee7a1febd29dce54c5499c54e7f5f980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::WebAssembly::getStackOpcode (unsigned short Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-h">WebAssemblyTargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a>.</p>

</div>
</div>

### getWARegStackId() {#ad3603fdd430b146d72370dd19afa46d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WebAssembly::getWARegStackId (unsigned Reg)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>.</p>

</div>
</div>

### getWasm64Opcode() {#a076d4939d577df2c4f5ddbb3bb807f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::WebAssembly::getWasm64Opcode (unsigned short Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-h">WebAssemblyTargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### isArgument() {#a15296a1aa48a333f25583e31fd8f2a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isArgument (unsigned Opc)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp/#a0cad575df04ef66a39c5d0d0501cf267">addImplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp/#a0b242745d9d1004fe6148b674533afb2">hasArgumentDef</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#aa44a7b836eacb5db2df92e3ae85693ef">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::runOnMachineFunction</a>.</p>

</div>
</div>

### isBrTable() {#a3f816bb54827dac93c4d2c64ecad7878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isBrTable (unsigned Opc)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isCallDirect() {#ac361b53d0a877031bfd4b8b4e52b853f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isCallDirect (unsigned Opc)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isCallIndirect() {#a20f95094c89d3bf2738057a3278bf6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isCallIndirect (unsigned Opc)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a> and <a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a>.</p>

</div>
</div>

### isCatch() {#a6e775f5df24e1c131a9e1840877503ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isCatch (unsigned Opc)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="#a6cc6351696a872f05cdf540a663d584c">findCatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>.</p>

</div>
</div>

### isCatchAll() {#a2c7b0bfa782962c21346bf0c7f463d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isCatchAll (unsigned Opc)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isChild() {#a1403d0f29e96c05811fe277c8c68eae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isChild (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo">WebAssemblyFunctionInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether MI is a child of some other node in an expression tree.</p>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a06bf1d7d3fad0e5185a4ff892c7ad4a5">llvm::WebAssemblyFunctionInfo::isVRegStackified</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isConst() {#a96aa429fc26326800379bb06512648ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isConst (unsigned Opc)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isCopy() {#a850b55e79066ad88588cfb6b740f8655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isCopy (unsigned Opc)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isDefaultAddressSpace() {#a0b4dff4ccfc2539f59ef6bd15dc5e629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isDefaultAddressSpace (unsigned AS)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/wasmaddressspaces-h">WasmAddressSpaces.h</a>.</p>


<p>Reference <a href="#a4dfe79d002517ae351f8af2245726c78a28b2cdf56b37b7d93db4aa3850682dd1">WASM_ADDRESS_SPACE_DEFAULT</a>.</p>


<p>Referenced by <a href="#a8eacdd4ec3308700b0783d15978f9e54">isValidAddressSpace</a>.</p>

</div>
</div>

### isEndMarker() {#a4d6a3f5d24c97c850346915bc114e4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isEndMarker (unsigned Opc)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isLocalGet() {#af4b0f07eeb2793f36db70e3a80b736df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isLocalGet (unsigned Opc)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isLocalSet() {#ae107f1555331a3422b7fbfe1b85d82dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isLocalSet (unsigned Opc)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a5255e72bcf98efe146a049652e01d308">llvm::WebAssemblyInstrInfo::isExplicitTargetIndexDef</a>.</p>

</div>
</div>

### isLocalTee() {#a1124cde121d57efe04ea42bc165eb583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isLocalTee (unsigned Opc)</td>
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



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a5255e72bcf98efe146a049652e01d308">llvm::WebAssemblyInstrInfo::isExplicitTargetIndexDef</a>.</p>

</div>
</div>

### isMarker() {#a3982a1bf74ed2e218a45c7894fc660ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isMarker (unsigned Opc)</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="#a6cc6351696a872f05cdf540a663d584c">findCatch</a>.</p>

</div>
</div>

### isRefType() {#a67cf3dad6e6b882d8cbf39de2ded9558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isRefType (<a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> Type)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a429e2e7f86760397481df696c53a6bb3">llvm::wasm::EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a4940799cc4a5c058f96344ec55c38f51">llvm::wasm::EXTERNREF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>.</p>

</div>
</div>

### isScalarConst() {#ad31ca7d5649f6d16c56eba98634d60f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isScalarConst (unsigned Opc)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>.</p>

</div>
</div>

### isTee() {#a8fd4c79cd9af314c5d43043e10dcb0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isTee (unsigned Opc)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a598eeebd324ee0050cc856e6e28f4778">unstackifyVRegsUsedInSplitBB</a>.</p>

</div>
</div>

### isTry() {#a16f9d59e0218f930dedb4725b6df7371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isTry (unsigned Opc)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### isValidAddressSpace() {#a8eacdd4ec3308700b0783d15978f9e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isValidAddressSpace (unsigned AS)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/wasmaddressspaces-h">WasmAddressSpaces.h</a>.</p>


<p>References <a href="#a0b4dff4ccfc2539f59ef6bd15dc5e629">isDefaultAddressSpace</a> and <a href="#af45a1b676eb96b330c6a5bb5dab029ae">isWasmVarAddressSpace</a>.</p>

</div>
</div>

### isWasmVarAddressSpace() {#af45a1b676eb96b330c6a5bb5dab029ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isWasmVarAddressSpace (unsigned AS)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/wasmaddressspaces-h">WasmAddressSpaces.h</a>.</p>


<p>Reference <a href="#a4dfe79d002517ae351f8af2245726c78ad65bc6cefc871511e30423f55a1a4148">WASM_ADDRESS_SPACE_VAR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#af0cbac92300c3074e6bb81d58e92a86b">llvm::WebAssemblyAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="#a8eacdd4ec3308700b0783d15978f9e54">isValidAddressSpace</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a8deafd57e22779c013b2225fa89866ce">IsWebAssemblyGlobal</a>.</p>

</div>
</div>

### isWebAssemblyExternrefType() {#a1a9e7ebbbd5f298ad775c53afeff637c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isWebAssemblyExternrefType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Externref <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>.</p>


<p>Reference <a href="#a4dfe79d002517ae351f8af2245726c78a163c951c2848a11c33a29027580276c5">WASM_ADDRESS_SPACE_EXTERNREF</a>.</p>


<p>Referenced by <a href="#a6be40d1caf33e1e14d176d2a714b760c">isWebAssemblyReferenceType</a> and <a href="#a711350a8af2fb95f4f1ca8cb7fa79374">wasmSymbolSetType</a>.</p>

</div>
</div>

### isWebAssemblyFuncrefType() {#a5de30f2c5dd4809d2b8261f23e8d7e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isWebAssemblyFuncrefType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Funcref <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>.</p>


<p>Reference <a href="#a4dfe79d002517ae351f8af2245726c78af415dccc1391c50d45ec321f55292939">WASM_ADDRESS_SPACE_FUNCREF</a>.</p>


<p>Referenced by <a href="#a6be40d1caf33e1e14d176d2a714b760c">isWebAssemblyReferenceType</a> and <a href="#a711350a8af2fb95f4f1ca8cb7fa79374">wasmSymbolSetType</a>.</p>

</div>
</div>

### isWebAssemblyReferenceType() {#a6be40d1caf33e1e14d176d2a714b760c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isWebAssemblyReferenceType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if this is a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Reference <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>.</p>


<p>References <a href="#a1a9e7ebbbd5f298ad775c53afeff637c">isWebAssemblyExternrefType</a> and <a href="#a5de30f2c5dd4809d2b8261f23e8d7e6e">isWebAssemblyFuncrefType</a>.</p>


<p>Referenced by <a href="#a6edd1388aabcf34144b4bbbea08ee00d">isWebAssemblyTableType</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>.</p>

</div>
</div>

### isWebAssemblyTableType() {#a6edd1388aabcf34144b4bbbea08ee00d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::isWebAssemblyTableType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if the table represents a <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> table type.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>.</p>


<p>Reference <a href="#a6be40d1caf33e1e14d176d2a714b760c">isWebAssemblyReferenceType</a>.</p>


<p>Referenced by <a href="#a711350a8af2fb95f4f1ca8cb7fa79374">wasmSymbolSetType</a>.</p>

</div>
</div>

### mayThrow() {#ab6548436b77ac06129373db3d8e3dece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssembly::mayThrow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05fda0e278d12242b0e6026ec6b23643">CxaBeginCatchFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a59640be12351dbd3b6a2914e5ab386a7">getCalleeOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab59b255f78cd503133d032152a41d105">llvm::MachineOperand::getSymbolName</a>, <a href="#a20f95094c89d3bf2738057a3278bf6b4">isCallIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7c5f0ef161b5b4dedad2e9aac9fcfee7">llvm::MachineOperand::isSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a905f7fa7e3adde06b01c794635b5c8a5">PersonalityWrapperFn</a> and <a href="#a01758e2eef813342e32cce438ce1af58">StdTerminateFn</a>.</p>

</div>
</div>

### parseBlockType() {#a36696bf11093560ddae04b19b3e6857a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssembly::BlockType llvm::WebAssembly::parseBlockType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4a81eac01ea412ff384d2b5cb3cc8ebc0a">Exnref</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4acfebcdb871bec28e8e49332e4c71c578">Externref</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4a44ad4ef5a76e6aa6fb3e3fa079a54fda">F32</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4a1ad5f6f3069070ec4cbbdc94d5e61e0e">F64</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4a2d7df65515abbb3ea6189c510ecbaaac">Funcref</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4ad878ea6016bfe01729548bf442de5a8b">I32</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4ae7e62f6928f76df671b5a0379793fab6">I64</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4a4bbb8f967da6d1a610596d7257179c2b">Invalid</a>, <a href="#a9ebf832762357f1668dbc7fd07668de4ac6e36782efab8dde234ebf42882bcd55">V128</a> and <a href="#a9ebf832762357f1668dbc7fd07668de4a81ceb48a978444906d80119200aa358d">Void</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>.</p>

</div>
</div>

### parseMVT() {#ad633bade17028bdef34a0637c012eeb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::WebAssembly::parseMVT (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-cpp">WebAssemblyTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#adeea4dff058fbf427bf9b0dd9462e61c">llvm::WebAssemblyFunctionInfo::initializeBaseYamlFields</a>.</p>

</div>
</div>

### parseType() {#ae55eace303da656ab895760ed2f6da26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; wasm::ValType &gt; llvm::WebAssembly::parseType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a429e2e7f86760397481df696c53a6bb3">llvm::wasm::EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a4940799cc4a5c058f96344ec55c38f51">llvm::wasm::EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::wasm::F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::wasm::F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ad878ea6016bfe01729548bf442de5a8b">llvm::wasm::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ae7e62f6928f76df671b5a0379793fab6">llvm::wasm::I64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ac6e36782efab8dde234ebf42882bcd55">llvm::wasm::V128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ae7ca0cd3a609ecb42b8e91531f48bc28">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseRegTypeList</a>.</p>

</div>
</div>

### regClassToValType() {#a3af26fa5743569531580fe2e12eb594d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::ValType llvm::WebAssembly::regClassToValType (unsigned RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a429e2e7f86760397481df696c53a6bb3">llvm::wasm::EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a4940799cc4a5c058f96344ec55c38f51">llvm::wasm::EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::wasm::F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::wasm::F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ad878ea6016bfe01729548bf442de5a8b">llvm::wasm::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ae7e62f6928f76df671b5a0379793fab6">llvm::wasm::I64</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ac6e36782efab8dde234ebf42882bcd55">llvm::wasm::V128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a>.</p>

</div>
</div>

### signatureToString() {#ab777621cd8cd052180667366c7191456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::WebAssembly::signatureToString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> * Sig)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature/#ac0ca79970289bfc5eca95132b5cd1562">llvm::wasm::WasmSignature::Params</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature/#ab9eed93a9142e4a73b647f0eacbd0698">llvm::wasm::WasmSignature::Returns</a> and <a href="#ace38cf69cdffc766897324c5c07e6007">typeListToString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#a3d00e1ac3848f4af6f98182dca6f5045">llvm::WebAssemblyTargetAsmStreamer::emitFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#acfb93588e65e2c1c3e35ba88168478c5">llvm::WebAssemblyAsmPrinter::getMCSymbolForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a1e65050ef81c565f23ba4028e368c5fc">llvm::WebAssemblyInstPrinter::printWebAssemblySignatureOperand</a>.</p>

</div>
</div>

### toValType() {#a623013f677a44a584a4fad200887a4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::ValType llvm::WebAssembly::toValType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-cpp">WebAssemblyTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a429e2e7f86760397481df696c53a6bb3">llvm::wasm::EXNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a4940799cc4a5c058f96344ec55c38f51">llvm::wasm::EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::wasm::F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::wasm::F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ad878ea6016bfe01729548bf442de5a8b">llvm::wasm::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ae7e62f6928f76df671b5a0379793fab6">llvm::wasm::I64</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ac6e36782efab8dde234ebf42882bcd55">llvm::wasm::V128</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abf8d332ecf62a0b283e3795bdbd45d79">llvm::valTypesFromMVTs</a> and <a href="#a711350a8af2fb95f4f1ca8cb7fa79374">wasmSymbolSetType</a>.</p>

</div>
</div>

### typeListToString() {#ace38cf69cdffc766897324c5c07e6007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::WebAssembly::typeListToString (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> &gt; List)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="#a11bf36ed68b39005def2a7105a789863">typeToString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ad431095019a0f5c940ea308e3bcfadbf">llvm::WebAssemblyTargetAsmStreamer::emitTagType</a> and <a href="#ab777621cd8cd052180667366c7191456">signatureToString</a>.</p>

</div>
</div>

### typeToString() {#a11bf36ed68b39005def2a7105a789863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::WebAssembly::typeToString (<a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8">wasm::ValType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a>.</p>


<p>Reference <a href="#ac4634f1f44bd5719bcbc73540b0e23e5">anyTypeToString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#aa2841293de9505ceb9ef958d38fa1526">llvm::WebAssemblyTargetAsmStreamer::emitGlobalType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetasmstreamer/#ab1be13e43fafccdcb3c7fb6ff5b316e5">llvm::WebAssemblyTargetAsmStreamer::emitTableType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblytargetstreamer-cpp/#a247c7c30ea4266b5fe67c834628e1981">printTypes</a> and <a href="#ace38cf69cdffc766897324c5c07e6007">typeListToString</a>.</p>

</div>
</div>

### wasmSymbolSetType() {#a711350a8af2fb95f4f1ca8cb7fa79374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::WebAssembly::wasmSymbolSetType (<a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * GlobalVT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &gt; VTs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets a Wasm Symbol <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-cpp">WebAssemblyTypeUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a4940799cc4a5c058f96344ec55c38f51">llvm::wasm::EXTERNREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8a56830bd472296f98c7672a39085926ae">llvm::wasm::FUNCREF</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3fb19a71e602dce8ff646c3ac2f4ca0f">llvm::Type::getArrayElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af3dcaf743b04a6ee2c241b2259959b4a">llvm::MCSymbolWasm::getType</a>, <a href="#a1a9e7ebbbd5f298ad775c53afeff637c">isWebAssemblyExternrefType</a>, <a href="#a5de30f2c5dd4809d2b8261f23e8d7e6e">isWebAssemblyFuncrefType</a>, <a href="#a6edd1388aabcf34144b4bbbea08ee00d">isWebAssemblyTableType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a8b778bb98433efd9a6630bb45b4bd64f">llvm::MCSymbolWasm::setGlobalType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a044b57ea7f09bf315fe429350de59d25">llvm::MCSymbolWasm::setTableType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a817a67945b1632513e9b43ca0da9aacd">llvm::MCSymbolWasm::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="#a623013f677a44a584a4fad200887a4a0">toValType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ClangCallTerminateFn {#a9b8421ef1abb7fb4c5c61d8954924c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::WebAssembly::ClangCallTerminateFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>.</p>

</div>
</div>

### CxaBeginCatchFn {#a05fda0e278d12242b0e6026ec6b23643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::WebAssembly::CxaBeginCatchFn = "__cxa_begin_catch"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>Referenced by <a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a>.</p>

</div>
</div>

### CxaRethrowFn {#a26e7caa6d9b0e8793080c9af8f8a3441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::WebAssembly::CxaRethrowFn = "__cxa_rethrow"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>

</div>
</div>

### End {#a905cd49db07f7404b218ee58818c80a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::WebAssembly::End = 0x0b</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>

</div>
</div>

### Nop {#a8252c3c3e2c889ea98eea628b81d2999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::WebAssembly::Nop = 0x01</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> opcodes emitted via means other than CodeGen.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmbackend-cpp-/webassemblyasmbackend/#a867e27e3e5a5b56aaead9f73a584bcd2">anonymous{WebAssemblyAsmBackend.cpp}::WebAssemblyAsmBackend::writeNopData</a>.</p>

</div>
</div>

### PersonalityWrapperFn {#a905f7fa7e3adde06b01c794635b5c8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::WebAssembly::PersonalityWrapperFn</td>
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
<div class="doxyVerbatim">=
    "_Unwind_Wasm_CallPersonality"
</div>
</dd>
</dl>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>Referenced by <a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a>.</p>

</div>
</div>

### StdTerminateFn {#a01758e2eef813342e32cce438ce1af58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::WebAssembly::StdTerminateFn = "_ZSt9terminatev"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a>.</p>


<p>Referenced by <a href="#ab6548436b77ac06129373db3d8e3dece">mayThrow</a>.</p>

</div>
</div>

### UnusedReg {#a77bfe2fcd74307eb34fab682645aea2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::WebAssembly::UnusedReg = -1u</td>
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



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a3c87bc98c0134ce9b3b6ba21ec7020d5">llvm::WebAssemblyFunctionInfo::initWARegs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a4be1a6a79f3264e8f35ac342046322a4">llvm::WebAssemblyInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4c5b93703bfd35ff033b6fd30c2b8ee7">llvm::WebAssemblyAsmPrinter::regToString</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a6c521472c6da6834fae5613839fc5ef9">llvm::WebAssemblyFunctionInfo::setWAReg</a>.</p>

</div>
</div>

### WasmEnableEH {#a83d68f56b86e580ac9d156b47af53c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::WebAssembly::WasmEnableEH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblymcasminfo/#aeedabbbedf55686897e99e0f50249f66">llvm::WebAssemblyMCAsmInfo::WebAssemblyMCAsmInfo</a>.</p>

</div>
</div>

### WasmEnableEmEH {#a9d507b0cb1cf288e6fe831666a8b8668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::WebAssembly::WasmEnableEmEH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aa29ca0ef805870463b1abf3171c5cf1c">llvm::WebAssemblyAsmPrinter::emitDecls</a>.</p>

</div>
</div>

### WasmEnableEmSjLj {#aab16d00c5762ae8f5a89ce045b44b07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::WebAssembly::WasmEnableEmSjLj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aa29ca0ef805870463b1abf3171c5cf1c">llvm::WebAssemblyAsmPrinter::emitDecls</a>.</p>

</div>
</div>

### WasmEnableSjLj {#a877b8fcf196f226d4f2289ebdb1f276b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::WebAssembly::WasmEnableSjLj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a2dacd2cc5f8d003dbbf793474f06df14">canLongjmp</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblymcasminfo/#aeedabbbedf55686897e99e0f50249f66">llvm::WebAssemblyMCAsmInfo::WebAssemblyMCAsmInfo</a>.</p>

</div>
</div>

### WasmUseLegacyEH {#a66b0b93d22f984ea3f11e3fc04dbe744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::WebAssembly::WasmUseLegacyEH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyiseldagtodag-cpp-/webassemblydagtodagisel/#ab80c137e562add63a0b2c3afbed31be2">anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::Select</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/wasmehfuncinfo-h">WasmEHFuncInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyfixupkinds-h">WebAssemblyFixupKinds.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">WebAssemblyMCTargetDesc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-cpp">WebAssemblyMCTypeUtilities.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctypeutilities-h">WebAssemblyMCTypeUtilities.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-h">WebAssemblyTargetInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/wasmaddressspaces-h">WasmAddressSpaces.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-cpp">WebAssemblyTypeUtilities.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/utils/webassemblytypeutilities-h">WebAssemblyTypeUtilities.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassembly-h">WebAssembly.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfastisel-cpp">WebAssemblyFastISel.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyinstrinfo-h">WebAssemblyInstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-h">WebAssemblyISelLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-cpp">WebAssemblyRuntimeLibcallSignatures.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyruntimelibcallsignatures-h">WebAssemblyRuntimeLibcallSignatures.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-cpp">WebAssemblyUtilities.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
