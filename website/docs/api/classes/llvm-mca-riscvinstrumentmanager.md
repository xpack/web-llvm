---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/riscvinstrumentmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVInstrumentManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::RISCVInstrumentManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">Target/RISCV/MCA/RISCVCustomBehaviour.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager">InstrumentManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class allows targets to optionally customize the logic that resolves scheduling class IDs. <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5b34c24369de4cdeb9a7d696a202c9">RISCVInstrumentManager</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88704c3b0a019c591cf0f8b89708e4e">shouldIgnoreInstruments</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if llvm-mca should ignore instruments. <a href="#af88704c3b0a019c591cf0f8b89708e4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd931b2cf0359a2362ded0337a0bd2e">supportsInstrumentType</a> (StringRef Type) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mca/#a33806b50f8cfeb26c86a2d73207ea71e">UniqueInstrument</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59287a7fd62fcd4c1a61f204b9c06bfb">createInstrument</a> (StringRef Desc, StringRef Data) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> for RISC-V target. <a href="#a59287a7fd62fcd4c1a61f204b9c06bfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a33806b50f8cfeb26c86a2d73207ea71e">UniqueInstrument</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0185b56daf5bfb7ebff494d4ade9787">createInstruments</a> (const MCInst &amp;Inst) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a list of unique pointers to Instruments, where each <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> is allocated by this function. <a href="#ae0185b56daf5bfb7ebff494d4ade9787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565ec0f78fe6a37a593cf626b7d0c334">getSchedClassID</a> (const MCInstrInfo &amp;MCII, const MCInst &amp;MCI, const SmallVector&lt; Instrument * &gt; &amp;IVec) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Using the <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a>, returns a SchedClassID to use instead of the SchedClassID that belongs to the MCI or the original SchedClassID. <a href="#a565ec0f78fe6a37a593cf626b7d0c334">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVInstrumentManager() {#afd5b34c24369de4cdeb9a7d696a202c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::RISCVInstrumentManager::RISCVInstrumentManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#a94189e246106cc5ea4de8e189367482e">llvm::mca::InstrumentManager::InstrumentManager</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#a34e53b6d8294808eaa4149030ea84437">llvm::mca::InstrumentManager::MCII</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#af15b8aa847f292c9be1e8bf5ee91142f">llvm::mca::InstrumentManager::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createInstrument() {#a59287a7fd62fcd4c1a61f204b9c06bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueInstrument llvm::mca::RISCVInstrumentManager::createInstrument (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Desc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> for RISC-V target.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp">RISCVCustomBehaviour.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#abbb4e47e3127fe910c25c5f468c0d306">llvm::mca::RISCVLMULInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a90479775cc967cd520613381ec996097">llvm::mca::RISCVSEWInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#a64b0f03818e2adfb7d040addcd629006">llvm::mca::RISCVLMULInstrument::isDataValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a415d385fae49859d685eb3c0aaf4c049">llvm::mca::RISCVSEWInstrument::isDataValid</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ae0185b56daf5bfb7ebff494d4ade9787">createInstruments</a>.</p>

</div>
</div>

### createInstruments() {#ae0185b56daf5bfb7ebff494d4ade9787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; UniqueInstrument &gt; llvm::mca::RISCVInstrumentManager::createInstruments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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

<p>Return a list of unique pointers to Instruments, where each <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> is allocated by this function.</p>


<p>See createInstrument to create <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> from a description and data.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp">RISCVCustomBehaviour.cpp</a>.</p>


<p>References <a href="#a59287a7fd62fcd4c1a61f204b9c06bfb">createInstrument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#abbb4e47e3127fe910c25c5f468c0d306">llvm::mca::RISCVLMULInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a90479775cc967cd520613381ec996097">llvm::mca::RISCVSEWInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#af5af8d664535a4bfbb71f0243ed9ae3a">llvm::RISCVVType::getSEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a12465125c9315bf864c53298cccde08a">llvm::RISCVVType::getVLMUL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca1fc4732c22ad534f1cec77512aa4c451">llvm::RISCVII::LMUL_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1cafc3cf026a9a458e993d77f9d723cffe7">llvm::RISCVII::LMUL_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca81b84a0b11f1c29695dbf7765f8ceaa7">llvm::RISCVII::LMUL_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1cae7fe853f54d8e8aaf63568ed61da11e0">llvm::RISCVII::LMUL_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caf5395daef0a34ae8d78919a587eee448">llvm::RISCVII::LMUL_F2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1caea5ed9248acd465f986c64e15db529e5">llvm::RISCVII::LMUL_F4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca61d90764106d2ac6346f4bc1ae1bd3fd">llvm::RISCVII::LMUL_F8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1ca2d6714f02f06560c3f5671e12e90d0bb">llvm::RISCVII::LMUL_RESERVED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc529c79977cdd01e187986f960a07f">llvm::SmallVector</a>.</p>

</div>
</div>

### getSchedClassID() {#a565ec0f78fe6a37a593cf626b7d0c334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RISCVInstrumentManager::getSchedClassID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a> * &gt; &amp; IVec)</td>
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

<p>Using the <a href="/web-llvm/docs/api/classes/llvm/mca/instrument">Instrument</a>, returns a SchedClassID to use instead of the SchedClassID that belongs to the MCI or the original SchedClassID.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp">RISCVCustomBehaviour.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#abbb4e47e3127fe910c25c5f468c0d306">llvm::mca::RISCVLMULInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a90479775cc967cd520613381ec996097">llvm::mca::RISCVSEWInstrument::DESC_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrument/#a05e8f923dee550affdcb2acca3a478a3">llvm::mca::Instrument::getData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ad0d97c2779bb2264df1ceeac09052e5a">llvm::mca::getEEWAndEMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#a5a931e7a3f5a08d5878c1cc9b2e4b9ad">llvm::mca::RISCVLMULInstrument::getLMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager/#a34e53b6d8294808eaa4149030ea84437">llvm::mca::InstrumentManager::MCII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a3c6092a8dbfcd644e83755117fcf31b0">llvm::mca::opcodeHasEEWAndEMULInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca2ce62e1cd502db9d1a7a8295164f6584">llvm::RVV</a>.</p>

</div>
</div>

### shouldIgnoreInstruments() {#af88704c3b0a019c591cf0f8b89708e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::RISCVInstrumentManager::shouldIgnoreInstruments ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if llvm-mca should ignore instruments.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>.</p>

</div>
</div>

### supportsInstrumentType() {#a3cd931b2cf0359a2362ded0337a0bd2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::RISCVInstrumentManager::supportsInstrumentType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp">RISCVCustomBehaviour.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#abbb4e47e3127fe910c25c5f468c0d306">llvm::mca::RISCVLMULInstrument::DESC_NAME</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a90479775cc967cd520613381ec996097">llvm::mca::RISCVSEWInstrument::DESC_NAME</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp">RISCVCustomBehaviour.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-h">RISCVCustomBehaviour.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
