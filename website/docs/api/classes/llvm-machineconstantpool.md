---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineconstantpool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineConstantPool` Class Reference

<p>The <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> class keeps track of constants referenced by a function which must be spilled to memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineConstantPool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482792470bfd3d7e4f1581f3c3f4bb14">MachineConstantPool</a> (const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The only constructor. <a href="#a482792470bfd3d7e4f1581f3c3f4bb14">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f7221bd67a58e2b773ad676e93d61c">~MachineConstantPool</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88baf3198734f788f149573046bcab2d">getConstantPoolAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment required by the whole constant pool, of which the first element must be aligned. <a href="#a88baf3198734f788f149573046bcab2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6691ddb5d4adf50d744297e18a1c6d">getConstantPoolIndex</a> (const Constant *C, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getConstantPoolIndex - Create a new entry in the constant pool or return an existing one. <a href="#afd6691ddb5d4adf50d744297e18a1c6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3483fa9fda4a1e205c68677733075b8">getConstantPoolIndex</a> (MachineConstantPoolValue *V, Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c580b99c8802f7c6c514c2884377c1">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEmpty - Return true if this constant pool contains no constants. <a href="#af6c580b99c8802f7c6c514c2884377c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a906c142ea808e1bf1a66f59c4fb51048">getConstants</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0518b5b32ebcd3a174bc27c0d10c65">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about constant pool objects. <a href="#a9c0518b5b32ebcd3a174bc27c0d10c65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e78963698b00ac5f8adeb6c942d4a6">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Call print(cerr) to be called from the debugger. <a href="#a17e78963698b00ac5f8adeb6c942d4a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724701edd0bf0e450d9ba0b4492e0f29">getDataLayout</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b6d186ccb3ff4121a91075ab26ad70">PoolAlignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alignment for the pool. <a href="#ab6b6d186ccb3ff4121a91075ab26ad70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c098df3ab3b1b1fc021b83b78069c0">Constants</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pool of constants. <a href="#a40c098df3ab3b1b1fc021b83b78069c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue">MachineConstantPoolValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645f0eeac47890e6ee872e1ad4fe23df">MachineCPVsSharingEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MachineConstantPoolValues that use an existing <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a>. <a href="#a645f0eeac47890e6ee872e1ad4fe23df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1104057d698733c0dd29c9684ee3e2">DL</a></td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> class keeps track of constants referenced by a function which must be spilled to memory.</p>


<p>This is used for constants which are unable to be used directly as operands to instructions, which typically include floating point and large integer constants.</p>


<p>Instructions reference the address of these constant pool constants through the use of MO_ConstantPoolIndex values. When emitting assembly or machine code, these virtual address references are converted to refer to the address of the function constant pool values. The machine constant pool.</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineConstantPool() {#a482792470bfd3d7e4f1581f3c3f4bb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineConstantPool::MachineConstantPool (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The only constructor.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineConstantPool() {#ab1f7221bd67a58e2b773ad676e93d61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPool::~MachineConstantPool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a5fe6005bf6e415c950c011fb65f12b8f">Deleted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a17e78963698b00ac5f8adeb6c942d4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineConstantPool::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Call print(cerr) to be called from the debugger.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a9c0518b5b32ebcd3a174bc27c0d10c65">print</a>.</p>

</div>
</div>

### getConstantPoolAlign() {#a88baf3198734f788f149573046bcab2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineConstantPool::getConstantPoolAlign ()</td>
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

<p>Return the alignment required by the whole constant pool, of which the first element must be aligned.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

### getConstantPoolIndex() {#afd6691ddb5d4adf50d744297e18a1c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineConstantPool::getConstantPoolIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getConstantPoolIndex - Create a new entry in the constant pool or return an existing one.</p>


<p>Create a new entry in the constant pool or return an existing one.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> must specify the minimum required alignment for the object.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> must specify the log2 of the minimum required alignment for the object.</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#ab6ad9778a01cb685ae9a36e09ffedaab">CanShareConstantPoolEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4ca63570c656522c8e6a423ae926ba5e">llvm::XtensaInstrInfo::loadImmediate</a>.</p>

</div>
</div>

### getConstantPoolIndex() {#ab3483fa9fda4a1e205c68677733075b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineConstantPool::getConstantPoolIndex (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue">MachineConstantPoolValue</a> * V, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>

</div>
</div>

### getConstants() {#a906c142ea808e1bf1a66f59c4fb51048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; MachineConstantPoolEntry &gt; &amp; llvm::MachineConstantPool::getConstants ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a3be62931e10ef98f2b7f7151eac8c3d4">llvm::XtensaAsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a558790807cf5c060c4c82f09decb89d5">EstimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyframelowering-cpp/#a2e40689969f017c682539e2729fc1bb5">EstimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedca54ee65b84a32a3bf0c9a595e2fd9">llvm::PPCInstrInfo::getConstantFromConstantPool</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### isEmpty() {#af6c580b99c8802f7c6c514c2884377c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineConstantPool::isEmpty ()</td>
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

<p>isEmpty - Return true if this constant pool contains no constants.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

### print() {#a9c0518b5b32ebcd3a174bc27c0d10c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineConstantPool::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>print - Used by the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> printer to print information about constant pool objects.</p>


<p>Implemented in <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></p>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1586 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>Referenced by <a href="#a17e78963698b00ac5f8adeb6c942d4a6">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getDataLayout() {#a724701edd0bf0e450d9ba0b4492e0f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::MachineConstantPool::getDataLayout ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Constants {#a40c098df3ab3b1b1fc021b83b78069c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineConstantPoolEntry&gt; llvm::MachineConstantPool::Constants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pool of constants.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

### DL {#a5f1104057d698733c0dd29c9684ee3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::MachineConstantPool::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

### MachineCPVsSharingEntries {#a645f0eeac47890e6ee872e1ad4fe23df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;MachineConstantPoolValue*&gt; llvm::MachineConstantPool::MachineCPVsSharingEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MachineConstantPoolValues that use an existing <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a>.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

### PoolAlignment {#ab6b6d186ccb3ff4121a91075ab26ad70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineConstantPool::PoolAlignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alignment for the pool.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
