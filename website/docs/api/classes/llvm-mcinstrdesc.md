---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcinstrdesc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCInstrDesc` Class

<p>Describe properties that are true of each instruction in the target description file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCInstrDesc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7695bd2e20788ffc4b645533c018f26e">getOperandConstraint</a> (unsigned OpNum, MCOI::OperandConstraint Constraint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the specified operand constraint if it is present. <a href="#a7695bd2e20788ffc4b645533c018f26e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee50fcacb786c1fc56168a0c55a4e934">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the opcode number for this descriptor. <a href="#aee50fcacb786c1fc56168a0c55a4e934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca904e64ee29c8812ed34e632d3c947">getNumOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of declared MachineOperands for this MachineInstruction. <a href="#a0ca904e64ee29c8812ed34e632d3c947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3496944fcc473dfe584e6615503a7a76">getNumDefs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of MachineOperands that are register definitions. <a href="#a3496944fcc473dfe584e6615503a7a76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cd91a67e9972e665c43a85c5b53b9d">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return flags of this instruction. <a href="#a07cd91a67e9972e665c43a85c5b53b9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b4498f379214def45664d4cb31aaaa">isPreISelOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5781c13cce7ee39fe5cc54dcebccd8">isVariadic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction can have a variable number of operands. <a href="#ade5781c13cce7ee39fe5cc54dcebccd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e10f6539cad5809d0d09d3a8d41b62">hasOptionalDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this instruction has an optional definition, e.g. <a href="#a32e10f6539cad5809d0d09d3a8d41b62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2cee6d743bcfb8946e6dcc4a6cc443">isPseudo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a pseudo instruction that doesn't correspond to a real machine instruction. <a href="#afa2cee6d743bcfb8946e6dcc4a6cc443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d895f6b0f460931a8c5697a69e7bd25">isMetaInstruction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a meta instruction that doesn't produce any output in the form of executable instructions. <a href="#a5d895f6b0f460931a8c5697a69e7bd25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f126216efaf20e5865c3eb03b25cc7">isReturn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a return. <a href="#ad2f126216efaf20e5865c3eb03b25cc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad750b3821971522747198a5ba6c452ef">isAdd</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is an add instruction. <a href="#ad750b3821971522747198a5ba6c452ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23c5bed445884208f7ec2d30c1c5461">isTrap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a trap. <a href="#ae23c5bed445884208f7ec2d30c1c5461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb615a6012f7ac2b7c4532a00d4da54">isMoveReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a register to register move. <a href="#a4fb615a6012f7ac2b7c4532a00d4da54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1b2a98bb0ec92da21fc3ddf683ca71">isCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a call. <a href="#aae1b2a98bb0ec92da21fc3ddf683ca71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2873fbf12f07af66ef30bba31ae1eab2">isBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified instruction stops control flow from executing the instruction immediately following it. <a href="#a2873fbf12f07af66ef30bba31ae1eab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace405d3fb039de6393e50328397487be">isTerminator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction part of the terminator for a basic block. <a href="#ace405d3fb039de6393e50328397487be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6478037933f13d6d8d80e6a12cdf932d">isBranch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a conditional, unconditional, or indirect branch. <a href="#a6478037933f13d6d8d80e6a12cdf932d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c6750b0502a3f135abe68ccda8cb5c">isIndirectBranch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an indirect branch, such as a branch through a register. <a href="#a18c6750b0502a3f135abe68ccda8cb5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea73c4d0a4275b356a0d33ed0c6ccc58">isConditionalBranch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a branch which may fall through to the next instruction or may transfer control flow to some other block. <a href="#aea73c4d0a4275b356a0d33ed0c6ccc58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b64c22b6df0f389b301bd2a5b281462">isUnconditionalBranch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a branch which always transfers control flow to some other block. <a href="#a7b64c22b6df0f389b301bd2a5b281462">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a> (const MCInst &amp;MI, const MCRegisterInfo &amp;RI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a branch or an instruction which directly writes to the program counter. <a href="#a561df24be97e83b9ce73d964fd33b88d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8321bbb1eb127512df72cacd7c80509b">isPredicable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has a predicate operand that controls execution. <a href="#a8321bbb1eb127512df72cacd7c80509b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599abfa4b585b74d1efbd86b9dd1210a">isCompare</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a comparison. <a href="#a599abfa4b585b74d1efbd86b9dd1210a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae647821f2551fbecb8d5b11e36f2c365">isMoveImmediate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a move immediate (including conditional moves) instruction. <a href="#ae647821f2551fbecb8d5b11e36f2c365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17956eac852ce46558283d31435e5b41">isBitcast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a bitcast instruction. <a href="#a17956eac852ce46558283d31435e5b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7547c48ed80dd2eda2ddf5fcf1c22a">isSelect</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a select instruction. <a href="#a2b7547c48ed80dd2eda2ddf5fcf1c22a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9152684b86bc720d12b8efe7aaa7ea39">isNotDuplicable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction cannot be safely duplicated. <a href="#a9152684b86bc720d12b8efe7aaa7ea39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22983706e0a5c8298c10371a07929db">hasDelaySlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified instruction has a delay slot which must be filled by the code generator. <a href="#ad22983706e0a5c8298c10371a07929db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7d46e1ddd94170bf735bc98ab088d2">canFoldAsLoad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for instructions that can be folded as memory operands in other instructions. <a href="#a4e7d46e1ddd94170bf735bc98ab088d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea816f76f6a2af90a27fbf27d5e1012">isRegSequenceLike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic REG_SEQUENCE instructions. <a href="#afea816f76f6a2af90a27fbf27d5e1012">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9258019cf2b2d68637d0e95cb334f74">isExtractSubregLike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic EXTRACT_SUBREG instructions. <a href="#aa9258019cf2b2d68637d0e95cb334f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ed493088fa0c6e5ba90609edcc49b1">isInsertSubregLike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic INSERT_SUBREG instructions. <a href="#a10ed493088fa0c6e5ba90609edcc49b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0a21f299f95d1afa5d0d10c4e1354b">isConvergent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is convergent. <a href="#a3b0a21f299f95d1afa5d0d10c4e1354b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71778bd76509f16d25336d608d1ab61f">variadicOpsAreDefs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if variadic operands of this instruction are definitions. <a href="#a71778bd76509f16d25336d608d1ab61f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec867a6cb8e5983da93b8dda910af821">isAuthenticated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction authenticates a pointer (e.g. <a href="#aec867a6cb8e5983da93b8dda910af821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eae6ddcf171bdfe8cde452311ff4160">mayLoad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly read memory. <a href="#a2eae6ddcf171bdfe8cde452311ff4160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1652b3fb1337b788da41bd95a348990c">mayStore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly modify memory. <a href="#a1652b3fb1337b788da41bd95a348990c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c717d314d03140128c2b249dc39b31">mayRaiseFPException</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may raise a floating-point exception. <a href="#a79c717d314d03140128c2b249dc39b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927b12dc654f2d95fbaf6a2d2ef67e68">hasUnmodeledSideEffects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has side effects that are not modeled by other flags. <a href="#a927b12dc654f2d95fbaf6a2d2ef67e68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8b632d74a4d458f9a1a95efa691dbd">isCommutable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this may be a 2- or 3-address instruction (of the form "X = op Y, Z, ..."), which produces the same result if Y and Z are exchanged. <a href="#a8c8b632d74a4d458f9a1a95efa691dbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb70d3633753f3ca1330d949bef683e7">isConvertibleTo3Addr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 2-address instruction which can be changed into a 3-address instruction if needed. <a href="#abb70d3633753f3ca1330d949bef683e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26cbe46f02506e823998e5ae5495cf39">usesCustomInsertionHook</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction requires custom insertion support when the DAG scheduler is inserting it into a machine basic block. <a href="#a26cbe46f02506e823998e5ae5495cf39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b72e41a6cdf1fef26fe0b0d2827779">hasPostISelHook</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction requires <em>adjustment</em> after instruction selection by calling a target hook. <a href="#aa2b72e41a6cdf1fef26fe0b0d2827779">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ba710f48d013966d1949667e263e8d">isRematerializable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction is a candidate for remat. <a href="#a56ba710f48d013966d1949667e263e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4f0d8f211f41b42adcf08ed3f098b9">isAsCheapAsAMove</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction has the same cost (or less) than a move instruction. <a href="#a2d4f0d8f211f41b42adcf08ed3f098b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1cfedba287e783eeea8becd8737e28">hasExtraSrcRegAllocReq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction source operands have special register allocation requirements that are not captured by the operand register classes. <a href="#aff1cfedba287e783eeea8becd8737e28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b7c6bc13b8c3e556b0b504a7311f43">hasExtraDefRegAllocReq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction def operands have special register allocation requirements that are not captured by the operand register classes. <a href="#a76b7c6bc13b8c3e556b0b504a7311f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">implicit_uses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a list of registers that are potentially read by any instance of this machine instruction. <a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a list of registers that are potentially written by any instance of this machine instruction. <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ac9abaa969c4e2801c8c4cdf1dde72">hasImplicitUseOfPhysReg</a> (MCRegister Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction implicitly uses the specified physical register. <a href="#ae5ac9abaa969c4e2801c8c4cdf1dde72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a">hasImplicitDefOfPhysReg</a> (MCRegister Reg, const MCRegisterInfo *MRI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction implicitly defines the specified physical register. <a href="#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a564c2840cb8d27314596549fc04b8">getSchedClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the scheduling class for this instruction. <a href="#a03a564c2840cb8d27314596549fc04b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad675c21464eb38c355e73c7f72f8160b">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes in the encoding of this instruction, or zero if the encoding size cannot be known from the opcode. <a href="#ad675c21464eb38c355e73c7f72f8160b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c5f527cd23f92a2b2ad6b1e117d8a6">findFirstPredOperandIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the index of the first operand in the operand list that is used to represent the predicate. <a href="#a19c5f527cd23f92a2b2ad6b1e117d8a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a> (const MCInst &amp;MI, MCRegister Reg, const MCRegisterInfo &amp;RI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction defines the specified physical register, either explicitly or implicitly. <a href="#a53879499740e1ed3770a41e9a444ee5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb5f001406dc2b45024dd582c444e6d">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c07a5f15c9d1ccad93dc1c57f79c09">NumOperands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ad82efc4fd3797a5d9ed70a55354c8">NumDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7beb150af9f64d18273d4a98ff37dec0">Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee44339b41568c74881f90122fee878">SchedClass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0213025f97776e13649b1136bae07524">NumImplicitUses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d45da21f713463669876b3efeaeb95a">NumImplicitDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2059c24fbfb9da805c6da6073ae60915">ImplicitOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc35bbedc928d6945522a0b6e3499759">OpInfoOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e0fcca2366f30d5e35b3d7dcb9c65f">TSFlags</a></td>
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

<p>Describe properties that are true of each instruction in the target description file.</p>


<p>This captures information about side effects, register use and many other things. There is one instance of this struct for each target instruction class, and the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> class points to this struct directly to describe itself.</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### canFoldAsLoad() {#a4e7d46e1ddd94170bf735bc98ab088d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::canFoldAsLoad ()</td>
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

<p>Return true for instructions that can be folded as memory operands in other instructions.</p>


<p>The most common use for this is instructions that are simple loads from memory that don't modify the loaded value in any way, but it can also be used for instructions that can be expressed as constant-pool loads, such as V_SETALLONES on x86, to allow them to be folded when it is beneficial. This should only be set on instructions that return a value in their only virtual register definition.</p>


<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aae43507b1a7708c07602a361936f7de3">llvm::MCID::FoldableAsLoad</a>.</p>

</div>
</div>

### findFirstPredOperandIdx() {#a19c5f527cd23f92a2b2ad6b1e117d8a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MCInstrDesc::findFirstPredOperandIdx ()</td>
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

<p>Find the index of the first operand in the operand list that is used to represent the predicate.</p>


<p>It returns -1 if none is found.</p>


<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a0ca904e64ee29c8812ed34e632d3c947">getNumOperands</a>, <a href="#a8321bbb1eb127512df72cacd7c80509b">isPredicable</a> and <a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a>.</p>

</div>
</div>

### getFlags() {#a07cd91a67e9972e665c43a85c5b53b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCInstrDesc::getFlags ()</td>
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

<p>Return flags of this instruction.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a257b68a68cb55f34cb704eb776afda1e">llvm::MachineInstr::hasProperty</a>.</p>

</div>
</div>

### getNumDefs() {#a3496944fcc473dfe584e6615503a7a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInstrDesc::getNumDefs ()</td>
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

<p>Return the number of MachineOperands that are register definitions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> definitions always occur at the start of the machine operand list. This is the number of "outs" in the .td file, and does not include implicit defs.</p>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#af3ad82efc4fd3797a5d9ed70a55354c8">NumDefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a31aa4c781d7a65b275b3de1882180675">llvm::SIInstrInfo::buildShrunkInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#aeec24c6aa6a3c47f2fc288478428e00d">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmccodeemitter-cpp/#a69f8a6a325901e0745c40c9f13c1a77d">hasType</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae40b5614303ad840c02bf2923d5f4305">llvm::ResourcePriorityQueue::initNumRegDefsLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac485643e66f0cec45d40f99288d3e25c">llvm::HexagonInstrInfo::isDependent</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/#acd87bac3058ade9f773fd2c79abdde8d">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::markDPProducersConsumers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aef788a4cb082ca5268ed346517eede15">llvm::mca::verifyOperands</a>.</p>

</div>
</div>

### getNumOperands() {#a0ca904e64ee29c8812ed34e632d3c947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInstrDesc::getNumOperands ()</td>
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

<p>Return the number of declared MachineOperands for this MachineInstruction.</p>


<p>Note that variadic (<a href="#ade5781c13cce7ee39fe5cc54dcebccd8">isVariadic()</a> returns true) instructions may have additional operands at the end of the list, and note that the machine instruction may include implicit register def/uses as well.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#a53c07a5f15c9d1ccad93dc1c57f79c09">NumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#aeec24c6aa6a3c47f2fc288478428e00d">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="#a19c5f527cd23f92a2b2ad6b1e117d8a6">findFirstPredOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac18c5827c119a73ea6f07b4ef4649654">llvm::SIInstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#aaec6e6ec16a011ef89299012d0dbe146">getTargetMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmccodeemitter-cpp/#a69f8a6a325901e0745c40c9f13c1a77d">hasType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/#acd87bac3058ade9f773fd2c79abdde8d">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::markDPProducersConsumers</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a538b1435d732f0d2620cea4849af80aa">llvm::SPIRVInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#ab9572d51415fe9448360292077d55435">llvm::SPIRVInstPrinter::printOpDecorate</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a5ae494d9fb7b6ef87715f462677938b9">llvm::SPIRVInstPrinter::printOpExtInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a9c82d545821ce74a71125df227cde299">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::usePopRet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aef788a4cb082ca5268ed346517eede15">llvm::mca::verifyOperands</a>.</p>

</div>
</div>

### getOpcode() {#aee50fcacb786c1fc56168a0c55a4e934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInstrDesc::getOpcode ()</td>
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

<p>Return the opcode number for this descriptor.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#adcb5f001406dc2b45024dd582c444e6d">Opcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a844dfba8ffcebffad1f2f43287740c96">llvm::AVRInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mc/#adea9a50e399e313a7a8a5b2007639b49">llvm::ARM_MC::evaluateBranchTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a781c6e7caca62cdc20d4e6a134425dd7">llvm::AMDGPU::hasAny64BitVGPROperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a370295a9498306cec66248f1c1fd8416">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeVectElement</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a572425344ad3846264384af43858a5e1">llvm::HexagonShuffler::shuffle</a>.</p>

</div>
</div>

### getOperandConstraint() {#a7695bd2e20788ffc4b645533c018f26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MCInstrDesc::getOperandConstraint (unsigned OpNum, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1">MCOI::OperandConstraint</a> Constraint)</td>
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

<p>Returns the value of the specified operand constraint if it is present.</p>


<p>Returns -1 if it is not present.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a53c07a5f15c9d1ccad93dc1c57f79c09">NumOperands</a> and <a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#aeec24c6aa6a3c47f2fc288478428e00d">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>.</p>

</div>
</div>

### getSchedClass() {#a03a564c2840cb8d27314596549fc04b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInstrDesc::getSchedClass ()</td>
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

<p>Return the scheduling class for this instruction.</p>


<p>The scheduling class is an index into the <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> table. This returns zero if there is no known scheduling information for the instruction.</p>


<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#abee44339b41568c74881f90122fee878">SchedClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dfapacketizer/#a7d2a8458e65d32d20a3ff84610bef308">llvm::DFAPacketizer::canReserveResources</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac4e5dcb952f0c76bcbb366a37077ecce">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#abbab66c4fbf9fd6512efa4efae8f69ef">llvm::HexagonInstrInfo::genAllInsnTimingClasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2913834d48cd087ac10ba131aae887a4">llvm::HexagonMCInstrInfo::getCVIResources</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a86ea143f1ea40632ba851badcf377101">llvm::TargetInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab488aa3ae070d9de98e958be991ea9cc">llvm::HexagonMCInstrInfo::getOtherReservedSlots</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac080bbec97a31ee8728ca9828700ad45">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a9211aa0b9d52257601df75d2818dab7c">llvm::HexagonMCInstrInfo::getUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#aa3867c828f38e2bf9dd517c69c682cc9">llvm::HexagonPacketizerList::ignorePseudoInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinepipeliner-cpp-/funcunitsorter/#a64d0e66977892f563370dbbcde3b8fc1">anonymous{MachinePipeliner.cpp}::FuncUnitSorter::minFuncUnits</a> and <a href="/web-llvm/docs/api/classes/llvm/dfapacketizer/#a9d9616a84ad6dd4722956b2765d5017b">llvm::DFAPacketizer::reserveResources</a>.</p>

</div>
</div>

### getSize() {#ad675c21464eb38c355e73c7f72f8160b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCInstrDesc::getSize ()</td>
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

<p>Return the number of bytes in the encoding of this instruction, or zero if the encoding size cannot be known from the opcode.</p>

<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Reference <a href="#a7beb150af9f64d18273d4a98ff37dec0">Size</a>.</p>

</div>
</div>

### hasDefOfPhysReg() {#a53879499740e1ed3770a41e9a444ee5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCInstrDesc::hasDefOfPhysReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction defines the specified physical register, either explicitly or implicitly.</p>

<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstrdesc-cpp">MCInstrDesc.cpp</a>.</p>


<p>References <a href="#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a">hasImplicitDefOfPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ac5ea214c523615af8b7c8c6547ef59de">llvm::MCRegisterInfo::isSubRegisterEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#af3ad82efc4fd3797a5d9ed70a55354c8">NumDefs</a>, <a href="#a53c07a5f15c9d1ccad93dc1c57f79c09">NumOperands</a> and <a href="#a71778bd76509f16d25336d608d1ab61f">variadicOpsAreDefs</a>.</p>


<p>Referenced by <a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a>.</p>

</div>
</div>

### hasDelaySlot() {#ad22983706e0a5c8298c10371a07929db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasDelaySlot ()</td>
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

<p>Returns true if the specified instruction has a delay slot which must be filled by the code generator.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a35dba8ebfddf32172dee2f54483c044a">llvm::MCID::DelaySlot</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### hasExtraDefRegAllocReq() {#a76b7c6bc13b8c3e556b0b504a7311f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasExtraDefRegAllocReq ()</td>
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

<p>Returns true if this instruction def operands have special register allocation requirements that are not captured by the operand register classes.</p>


<p>e.g. ARM::LDRD's two def registers must be an even / odd pair, ARM::LDM registers have to be in ascending order. Post-register allocation passes should not attempt to change allocations for definitions of instructions with this flag.</p>


<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a136b35119a9335091735d1faf665281d">llvm::MCID::ExtraDefRegAllocReq</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### hasExtraSrcRegAllocReq() {#aff1cfedba287e783eeea8becd8737e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasExtraSrcRegAllocReq ()</td>
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

<p>Returns true if this instruction source operands have special register allocation requirements that are not captured by the operand register classes.</p>


<p>e.g. ARM::STRD's two source registers must be an even / odd pair, ARM::STM registers have to be in ascending order. Post-register allocation passes should not attempt to change allocations for sources of instructions with this flag.</p>


<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a986397153989297cba4e0cf19b75412a">llvm::MCID::ExtraSrcRegAllocReq</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### hasImplicitDefOfPhysReg() {#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCInstrDesc::hasImplicitDefOfPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MRI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction implicitly defines the specified physical register.</p>

<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstrdesc-cpp">MCInstrDesc.cpp</a>.</p>


<p>References <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a> and <a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a>.</p>

</div>
</div>

### hasImplicitUseOfPhysReg() {#ae5ac9abaa969c4e2801c8c4cdf1dde72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasImplicitUseOfPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Return true if this instruction implicitly uses the specified physical register.</p>

<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">implicit_uses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>.</p>

</div>
</div>

### hasOptionalDef() {#a32e10f6539cad5809d0d09d3a8d41b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasOptionalDef ()</td>
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

<p>Set if this instruction has an optional definition, e.g.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> instructions which can set condition code if 's' bit is set.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a330ed49df68eb049e1a7f9f331a07d08">llvm::MCID::HasOptionalDef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aef788a4cb082ca5268ed346517eede15">llvm::mca::verifyOperands</a>.</p>

</div>
</div>

### hasPostISelHook() {#aa2b72e41a6cdf1fef26fe0b0d2827779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasPostISelHook ()</td>
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

<p>Return true if this instruction requires <em>adjustment</em> after instruction selection by calling a target hook.</p>


<p>For example, this can be used to fill in <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> 's' optional operand depending on whether the conditional flag register is used.</p>


<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a4dd7557d1d8cb30db26e0e28228c1cc7">llvm::MCID::HasPostISelHook</a>.</p>

</div>
</div>

### hasUnmodeledSideEffects() {#a927b12dc654f2d95fbaf6a2d2ef67e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::hasUnmodeledSideEffects ()</td>
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

<p>Return true if this instruction has side effects that are not modeled by other flags.</p>


<p>This does not return true for instructions whose effects are captured by:</p>


<ol class="doxyList" type="1">
<li>Their operand list and implicit definition/use list. <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> use/def info is explicit for instructions.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> accesses. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> mayLoad/mayStore.</li>
<li>Calling, branching, returning: use isCall/isReturn/isBranch.</li>
</ol>

<p>Examples of side effects would be modifying 'invisible' machine state like a control register, flushing a cache, modifying a register invisible to LLVM, etc.</p>


<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023af8bff71a05bf850313aede4b0f0af856">llvm::MCID::UnmodeledSideEffects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### implicit\_defs() {#a7b41627be5fb4176f9cb16b9ba7f91f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; llvm::MCInstrDesc::implicit_defs ()</td>
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

<p>Return a list of registers that are potentially written by any instance of this machine instruction.</p>


<p>For example, on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>, many instructions implicitly set the flags register. In this case, they are marked as setting the FLAGS. Likewise, many instructions always deposit their result in a physical register. For example, the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> divide instruction always deposits the quotient and remainder in the EAX/EDX registers. For that instruction, this will return a list containing the EAX/EDX/EFLAGS registers.</p>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a2059c24fbfb9da805c6da6073ae60915">ImplicitOffset</a>, <a href="#a0d45da21f713463669876b3efeaeb95a">NumImplicitDefs</a>, <a href="#a0213025f97776e13649b1136bae07524">NumImplicitUses</a> and <a href="#adcb5f001406dc2b45024dd582c444e6d">Opcode</a>.</p>


<p>Referenced by <a href="#aff7ca9d0ebf8c95da4ddd5bf28ac2e0a">hasImplicitDefOfPhysReg</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### implicit\_uses() {#aeae23d6b812a5aaa9734ebcdeb4f2d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; llvm::MCInstrDesc::implicit_uses ()</td>
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

<p>Return a list of registers that are potentially read by any instance of this machine instruction.</p>


<p>For example, on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>, the "adc" instruction adds two register operands and adds the carry bit in from the flags register. In this case, the instruction is marked as implicitly reading the flags. Likewise, the variable shift instruction on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> is marked as implicitly reading the 'CL' register, which it always does.</p>


<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a2059c24fbfb9da805c6da6073ae60915">ImplicitOffset</a>, <a href="#a0213025f97776e13649b1136bae07524">NumImplicitUses</a> and <a href="#adcb5f001406dc2b45024dd582c444e6d">Opcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="#ae5ac9abaa969c4e2801c8c4cdf1dde72">hasImplicitUseOfPhysReg</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### isAdd() {#ad750b3821971522747198a5ba6c452ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isAdd ()</td>
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

<p>Return true if the instruction is an add instruction.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a2b016c207343046b2bac45e69e76dcec">llvm::MCID::Add</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isAsCheapAsAMove() {#a2d4f0d8f211f41b42adcf08ed3f098b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isAsCheapAsAMove ()</td>
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

<p>Returns true if this instruction has the same cost (or less) than a move instruction.</p>


<p>This is useful during certain types of optimizations (e.g., remat during two-address conversion or machine licm) where we would like to remat or hoist the instruction, but not if it costs more than moving the instruction into the appropriate register. Note, we are not marking copies from and to the same register class with this flag.</p>


<p>This method could be called by interface <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9c5e9ccab2a323465af64b3661172af2">TargetInstrInfo::isAsCheapAsAMove</a> for different subtargets.</p>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a483f86b4470ddff0e7cf0e94253e07af">llvm::MCID::CheapAsAMove</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isAuthenticated() {#aec867a6cb8e5983da93b8dda910af821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isAuthenticated ()</td>
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

<p>Return true if this instruction authenticates a pointer (e.g.</p>


<p>LDRAx/BRAx from ARMv8.3, which perform loads/branches with authentication).</p>


<p>An authenticated instruction may fail in an ABI-defined manner when operating on an invalid signed pointer.</p>


<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023af08df35a985db315d7e9057ecbdff04d">llvm::MCID::Authenticated</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isBarrier() {#a2873fbf12f07af66ef30bba31ae1eab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isBarrier ()</td>
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

<p>Returns true if the specified instruction stops control flow from executing the instruction immediately following it.</p>


<p>Examples include unconditional branches and return instructions.</p>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a24b6e620b18edd37201fb9c0897835a8">llvm::MCID::Barrier</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>


<p>Referenced by <a href="#aea73c4d0a4275b356a0d33ed0c6ccc58">isConditionalBranch</a> and <a href="#a7b64c22b6df0f389b301bd2a5b281462">isUnconditionalBranch</a>.</p>

</div>
</div>

### isBitcast() {#a17956eac852ce46558283d31435e5b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isBitcast ()</td>
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

<p>Return true if this instruction is a bitcast instruction.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a1f4c637ab112633eebd0f503b71be732">llvm::MCID::Bitcast</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isBranch() {#a6478037933f13d6d8d80e6a12cdf932d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isBranch ()</td>
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

<p>Returns true if this is a conditional, unconditional, or indirect branch.</p>


<p>Predicates below can be used to discriminate between these cases, and the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a359237c780f7c8e40645575826da8a3c">llvm::MCID::Branch</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>


<p>Referenced by <a href="#aea73c4d0a4275b356a0d33ed0c6ccc58">isConditionalBranch</a>, <a href="#a7b64c22b6df0f389b301bd2a5b281462">isUnconditionalBranch</a> and <a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a>.</p>

</div>
</div>

### isCall() {#aae1b2a98bb0ec92da21fc3ddf683ca71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isCall ()</td>
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

<p>Return true if the instruction is a call.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a463baf545246fea9718664d933ffe66f">llvm::MCID::Call</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>


<p>Referenced by <a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a> and <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### isCommutable() {#a8c8b632d74a4d458f9a1a95efa691dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isCommutable ()</td>
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

<p>Return true if this may be a 2- or 3-address instruction (of the form "X = op Y, Z, ..."), which produces the same result if Y and Z are exchanged.</p>


<p>If this flag is set, then the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa41720cc33b0511709c92abcb164a59d">TargetInstrInfo::commuteInstruction</a> method may be used to hack on the instruction.</p>


<p>Note that this flag may be set on instructions that are only commutable sometimes. In these cases, the call to commuteInstruction will fail. Also note that some instructions require non-trivial modification to commute them.</p>


<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a3ef69fec39e2c626336993c9774dc406">llvm::MCID::Commutable</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isCompare() {#a599abfa4b585b74d1efbd86b9dd1210a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isCompare ()</td>
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

<p>Return true if this instruction is a comparison.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a1328ed43be8173506f59f88c9bfd8b8c">llvm::MCID::Compare</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isConditionalBranch() {#aea73c4d0a4275b356a0d33ed0c6ccc58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isConditionalBranch ()</td>
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

<p>Return true if this is a branch which may fall through to the next instruction or may transfer control flow to some other block.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information about this branch.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a2873fbf12f07af66ef30bba31ae1eab2">isBarrier</a>, <a href="#a6478037933f13d6d8d80e6a12cdf932d">isBranch</a> and <a href="#a18c6750b0502a3f135abe68ccda8cb5c">isIndirectBranch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>.</p>

</div>
</div>

### isConvergent() {#a3b0a21f299f95d1afa5d0d10c4e1354b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isConvergent ()</td>
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

<p>Return true if this instruction is convergent.</p>


<p>Convergent instructions may not be made control-dependent on any additional values.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a63a45e5b4f6037c05b07b9dc2c7ded46">llvm::MCID::Convergent</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isConvertibleTo3Addr() {#abb70d3633753f3ca1330d949bef683e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isConvertibleTo3Addr ()</td>
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

<p>Return true if this is a 2-address instruction which can be changed into a 3-address instruction if needed.</p>


<p>Doing this transformation can be profitable in the register allocator, because it means that the instruction can use a 2-address form if possible, but degrade into a less efficient form if the source and dest register cannot be assigned to the same register. For example, this allows the x86 backend to turn a "shl
reg, 3" instruction into an LEA instruction, which is the same speed as the shift but has bigger code size.</p>


<p>If this returns true, then the target must implement the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ada0a8cb9a764d058a63b77d50e9c0787">TargetInstrInfo::convertToThreeAddress</a> method for this instruction, which is allowed to fail if the transformation isn't valid for this specific instruction (e.g. shl reg, 4 on x86).</p>


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a4dc2f8bf7dec9f3153e6aed4db5cb010">llvm::MCID::ConvertibleTo3Addr</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isExtractSubregLike() {#aa9258019cf2b2d68637d0e95cb334f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isExtractSubregLike ()</td>
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

<p>Return true if this instruction behaves the same way as the generic EXTRACT_SUBREG instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, rX, rY VMOVRRD dZ is equivalent to two EXTRACT_SUBREG: rX = EXTRACT_SUBREG dZ, ssub_0 rY = EXTRACT_SUBREG dZ, ssub_1</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1c44734f854fb7f620d16097f2af637">TargetInstrInfo::getExtractSubregLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ade54f56905df7c591ac1baf60adf8ed5">llvm::MCID::ExtractSubreg</a> and <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a>.</p>

</div>
</div>

### isIndirectBranch() {#a18c6750b0502a3f135abe68ccda8cb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isIndirectBranch ()</td>
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

<p>Return true if this is an indirect branch, such as a branch through a register.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ac3c34b10dadcdbcc85552097cf077393">llvm::MCID::IndirectBranch</a>.</p>


<p>Referenced by <a href="#aea73c4d0a4275b356a0d33ed0c6ccc58">isConditionalBranch</a>, <a href="#a7b64c22b6df0f389b301bd2a5b281462">isUnconditionalBranch</a> and <a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a>.</p>

</div>
</div>

### isInsertSubregLike() {#a10ed493088fa0c6e5ba90609edcc49b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isInsertSubregLike ()</td>
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

<p>Return true if this instruction behaves the same way as the generic INSERT_SUBREG instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, dX = VSETLNi32 dY, rZ, Imm is equivalent to a INSERT_SUBREG: dX = INSERT_SUBREG dY, rZ, translateImmToSubIdx(Imm)</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2b51d2dd19b3859797509c03d5f451f1">TargetInstrInfo::getInsertSubregLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad36e4d09ad9fb9f039b446fa505149ad">llvm::MCID::InsertSubreg</a>.</p>

</div>
</div>

### isMetaInstruction() {#a5d895f6b0f460931a8c5697a69e7bd25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isMetaInstruction ()</td>
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

<p>Return true if this is a meta instruction that doesn't produce any output in the form of executable instructions.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad6fc37a26e7cdfb78a406be0ecf2f521">llvm::MCID::Meta</a>.</p>

</div>
</div>

### isMoveImmediate() {#ae647821f2551fbecb8d5b11e36f2c365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isMoveImmediate ()</td>
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

<p>Return true if this instruction is a move immediate (including conditional moves) instruction.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aaeaafb46babde1143b2fa296b164a5c4">llvm::MCID::MoveImm</a>.</p>

</div>
</div>

### isMoveReg() {#a4fb615a6012f7ac2b7c4532a00d4da54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isMoveReg ()</td>
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

<p>Return true if the instruction is a register to register move.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a37d39f9011275aa3445928f6b0037246">llvm::MCID::MoveReg</a>.</p>

</div>
</div>

### isNotDuplicable() {#a9152684b86bc720d12b8efe7aaa7ea39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isNotDuplicable ()</td>
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

<p>Return true if this instruction cannot be safely duplicated.</p>


<p>For example, if the instruction has a unique labels attached to it, duplicating it would cause multiple definition errors.</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a8c84f3a089d61a5e72ba0a166cf74e2c">llvm::MCID::NotDuplicable</a>.</p>

</div>
</div>

### isPredicable() {#a8321bbb1eb127512df72cacd7c80509b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isPredicable ()</td>
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

<p>Return true if this instruction has a predicate operand that controls execution.</p>


<p>It may be set to 'always', or may be set to other values. There are various methods in <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> that can be used to control and modify the predicate in this instruction.</p>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a9222c946b8b605c95952eedf035a7eff">llvm::MCID::Predicable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad22d00715292f5cf5d09380b15cb6189">DecodePredicateOperand</a> and <a href="#a19c5f527cd23f92a2b2ad6b1e117d8a6">findFirstPredOperandIdx</a>.</p>

</div>
</div>

### isPreISelOpcode() {#ae9b4498f379214def45664d4cb31aaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isPreISelOpcode ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this instruction is emitted before instruction selection and should be legalized/regbankselected/selected.</p></dd>
</dl>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a99de85e8619d9f7237f6434e655aa8af">llvm::MCID::PreISelOpcode</a>.</p>

</div>
</div>

### isPseudo() {#afa2cee6d743bcfb8946e6dcc4a6cc443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isPseudo ()</td>
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

<p>Return true if this is a pseudo instruction that doesn't correspond to a real machine instruction.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ab96d69e82db1bb1326a1d12b8a1e0076">llvm::MCID::Pseudo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab517da745358f306f00361d8280d020b">llvm::HexagonMCInstrInfo::isCanon</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>.</p>

</div>
</div>

### isRegSequenceLike() {#afea816f76f6a2af90a27fbf27d5e1012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isRegSequenceLike ()</td>
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

<p>Return true if this instruction behaves the same way as the generic REG_SEQUENCE instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, dX VMOVDRR rY, rZ is equivalent to dX = REG_SEQUENCE rY, ssub_0, rZ, ssub_1.</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a52e026925b73de52f7a563693ebff007">TargetInstrInfo::getRegSequenceLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aabce0250d60b95b97ff41ff41ba030d6">llvm::MCID::RegSequence</a>.</p>

</div>
</div>

### isRematerializable() {#a56ba710f48d013966d1949667e263e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isRematerializable ()</td>
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

<p>Returns true if this instruction is a candidate for remat.</p>


<p>This flag is only used in <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> method isTriviallyRematerializable.</p>


<p>If this flag is set, the isReallyTriviallyReMaterializable() method is called to verify the instruction is really rematerializable.</p>


<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a8862ede68c58eb6c127dc1f9fba7c8ab">llvm::MCID::Rematerializable</a>.</p>

</div>
</div>

### isReturn() {#ad2f126216efaf20e5865c3eb03b25cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isReturn ()</td>
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

<p>Return true if the instruction is a return.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a5416d9f1bd5f533efddadf17d713e469">llvm::MCID::Return</a>.</p>


<p>Referenced by <a href="#a561df24be97e83b9ce73d964fd33b88d">mayAffectControlFlow</a>.</p>

</div>
</div>

### isSelect() {#a2b7547c48ed80dd2eda2ddf5fcf1c22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isSelect ()</td>
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

<p>Return true if this is a select instruction.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a32dbd2c72a98eaee90e3ad5ef7b5af16">llvm::MCID::Select</a>.</p>

</div>
</div>

### isTerminator() {#ace405d3fb039de6393e50328397487be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isTerminator ()</td>
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

<p>Returns true if this instruction part of the terminator for a basic block.</p>


<p>Typically this is things like return and branch instructions.</p>


<p>Various passes use this to insert code into the bottom of a basic block, but before control flow occurs.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023af121d798d2c14b32e81d537a1f0cff8d">llvm::MCID::Terminator</a>.</p>

</div>
</div>

### isTrap() {#ae23c5bed445884208f7ec2d30c1c5461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isTrap ()</td>
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

<p>Return true if this instruction is a trap.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a07f4679af9a7f7ea34150e7f6354c0d2">llvm::MCID::Trap</a>.</p>

</div>
</div>

### isUnconditionalBranch() {#a7b64c22b6df0f389b301bd2a5b281462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isUnconditionalBranch ()</td>
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

<p>Return true if this is a branch which always transfers control flow to some other block.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information about this branch.</p>


<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a2873fbf12f07af66ef30bba31ae1eab2">isBarrier</a>, <a href="#a6478037933f13d6d8d80e6a12cdf932d">isBranch</a> and <a href="#a18c6750b0502a3f135abe68ccda8cb5c">isIndirectBranch</a>.</p>

</div>
</div>

### isVariadic() {#ade5781c13cce7ee39fe5cc54dcebccd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::isVariadic ()</td>
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

<p>Return true if this instruction can have a variable number of operands.</p>


<p>In this case, the variable operands will be after the normal operands but before the implicit definitions and uses (if any are present).</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a06448010e7faa3713221a1b768380957">llvm::MCID::Variadic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a538b1435d732f0d2620cea4849af80aa">llvm::SPIRVInstPrinter::printInst</a>.</p>

</div>
</div>

### mayAffectControlFlow() {#a561df24be97e83b9ce73d964fd33b88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCInstrDesc::mayAffectControlFlow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a branch or an instruction which directly writes to the program counter.</p>


<p>Considered 'may' affect rather than 'does' affect as things like predication are not taken into account.</p>


<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstrdesc-cpp">MCInstrDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a1ab4a7380910579b6946391cc8a7f77f">llvm::MCRegisterInfo::getProgramCounter</a>, <a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a>, <a href="#a6478037933f13d6d8d80e6a12cdf932d">isBranch</a>, <a href="#aae1b2a98bb0ec92da21fc3ddf683ca71">isCall</a>, <a href="#a18c6750b0502a3f135abe68ccda8cb5c">isIndirectBranch</a>, <a href="#ad2f126216efaf20e5865c3eb03b25cc7">isReturn</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### mayLoad() {#a2eae6ddcf171bdfe8cde452311ff4160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::mayLoad ()</td>
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

<p>Return true if this instruction could possibly read memory.</p>


<p>Instructions with this flag set are not necessarily simple load instructions, they may load a value and modify it, for example.</p>


<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a530d5e41c3cf67937c373da61c65acd4">llvm::MCID::MayLoad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>.</p>

</div>
</div>

### mayRaiseFPException() {#a79c717d314d03140128c2b249dc39b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::mayRaiseFPException ()</td>
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

<p>Return true if this instruction may raise a floating-point exception.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a6d8ad5d1cd35c1093591f1eb9512d3e8">llvm::MCID::MayRaiseFPException</a>.</p>

</div>
</div>

### mayStore() {#a1652b3fb1337b788da41bd95a348990c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::mayStore ()</td>
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

<p>Return true if this instruction could possibly modify memory.</p>


<p>Instructions with this flag set are not necessarily simple store instructions, they may store a modified value based on their operands, or may not actually modify anything, for example.</p>


<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a50b76935e53196d5d0610736ed52386d">llvm::MCID::MayStore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### operands() {#a0f4e09a761d45bf0914f26d4c149ddeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCOperandInfo &gt; llvm::MCInstrDesc::operands ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a53c07a5f15c9d1ccad93dc1c57f79c09">NumOperands</a>, <a href="#adcb5f001406dc2b45024dd582c444e6d">Opcode</a> and <a href="#afc35bbedc928d6945522a0b6e3499759">OpInfoOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/vopd/componentprops/#aeec24c6aa6a3c47f2fc288478428e00d">llvm::AMDGPU::VOPD::ComponentProps::ComponentProps</a>, <a href="#a19c5f527cd23f92a2b2ad6b1e117d8a6">findFirstPredOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="#a7695bd2e20788ffc4b645533c018f26e">getOperandConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac18c5827c119a73ea6f07b4ef4649654">llvm::SIInstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9dbc9a748353035febcc488160ba9956">llvm::MachineInstr::getTypeToPrint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a781c6e7caca62cdc20d4e6a134425dd7">llvm::AMDGPU::hasAny64BitVGPROperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmccodeemitter-cpp/#a69f8a6a325901e0745c40c9f13c1a77d">hasType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acbbc2f6b22e0c1dfd00546ef61cc0ac3">llvm::SIInstrInfo::isLegalToSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/#acd87bac3058ade9f773fd2c79abdde8d">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::markDPProducersConsumers</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a538b1435d732f0d2620cea4849af80aa">llvm::SPIRVInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>.</p>

</div>
</div>

### usesCustomInsertionHook() {#a26cbe46f02506e823998e5ae5495cf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::usesCustomInsertionHook ()</td>
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

<p>Return true if this instruction requires custom insertion support when the DAG scheduler is inserting it into a machine basic block.</p>


<p>If this is true for the instruction, it basically means that it is a pseudo instruction used at <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> time that is expanded out into magic code by the target when MachineInstrs are formed.</p>


<p>If this is true, the TargetLoweringInfo::InsertAtEndOfBasicBlock method is used to insert this into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad14700fd3b1c636ccbbdac0e94dd8bf9">llvm::MCID::UsesCustomInserter</a>.</p>

</div>
</div>

### variadicOpsAreDefs() {#a71778bd76509f16d25336d608d1ab61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstrDesc::variadicOpsAreDefs ()</td>
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

<p>Return true if variadic operands of this instruction are definitions.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>References <a href="#a27d4264231f86aafeaf8fb38e53342ee">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a3f20b8867db586190253ce9c9399cd3d">llvm::MCID::VariadicOpsAreDefs</a>.</p>


<p>Referenced by <a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a27d4264231f86aafeaf8fb38e53342ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCInstrDesc::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a4e7d46e1ddd94170bf735bc98ab088d2">canFoldAsLoad</a>, <a href="#a07cd91a67e9972e665c43a85c5b53b9d">getFlags</a>, <a href="#ad22983706e0a5c8298c10371a07929db">hasDelaySlot</a>, <a href="#a76b7c6bc13b8c3e556b0b504a7311f43">hasExtraDefRegAllocReq</a>, <a href="#aff1cfedba287e783eeea8becd8737e28">hasExtraSrcRegAllocReq</a>, <a href="#a32e10f6539cad5809d0d09d3a8d41b62">hasOptionalDef</a>, <a href="#aa2b72e41a6cdf1fef26fe0b0d2827779">hasPostISelHook</a>, <a href="#a927b12dc654f2d95fbaf6a2d2ef67e68">hasUnmodeledSideEffects</a>, <a href="#ad750b3821971522747198a5ba6c452ef">isAdd</a>, <a href="#a2d4f0d8f211f41b42adcf08ed3f098b9">isAsCheapAsAMove</a>, <a href="#aec867a6cb8e5983da93b8dda910af821">isAuthenticated</a>, <a href="#a2873fbf12f07af66ef30bba31ae1eab2">isBarrier</a>, <a href="#a17956eac852ce46558283d31435e5b41">isBitcast</a>, <a href="#a6478037933f13d6d8d80e6a12cdf932d">isBranch</a>, <a href="#aae1b2a98bb0ec92da21fc3ddf683ca71">isCall</a>, <a href="#a8c8b632d74a4d458f9a1a95efa691dbd">isCommutable</a>, <a href="#a599abfa4b585b74d1efbd86b9dd1210a">isCompare</a>, <a href="#a3b0a21f299f95d1afa5d0d10c4e1354b">isConvergent</a>, <a href="#abb70d3633753f3ca1330d949bef683e7">isConvertibleTo3Addr</a>, <a href="#aa9258019cf2b2d68637d0e95cb334f74">isExtractSubregLike</a>, <a href="#a18c6750b0502a3f135abe68ccda8cb5c">isIndirectBranch</a>, <a href="#a10ed493088fa0c6e5ba90609edcc49b1">isInsertSubregLike</a>, <a href="#a5d895f6b0f460931a8c5697a69e7bd25">isMetaInstruction</a>, <a href="#ae647821f2551fbecb8d5b11e36f2c365">isMoveImmediate</a>, <a href="#a4fb615a6012f7ac2b7c4532a00d4da54">isMoveReg</a>, <a href="#a9152684b86bc720d12b8efe7aaa7ea39">isNotDuplicable</a>, <a href="#a8321bbb1eb127512df72cacd7c80509b">isPredicable</a>, <a href="#ae9b4498f379214def45664d4cb31aaaa">isPreISelOpcode</a>, <a href="#afa2cee6d743bcfb8946e6dcc4a6cc443">isPseudo</a>, <a href="#afea816f76f6a2af90a27fbf27d5e1012">isRegSequenceLike</a>, <a href="#a56ba710f48d013966d1949667e263e8d">isRematerializable</a>, <a href="#ad2f126216efaf20e5865c3eb03b25cc7">isReturn</a>, <a href="#a2b7547c48ed80dd2eda2ddf5fcf1c22a">isSelect</a>, <a href="#ace405d3fb039de6393e50328397487be">isTerminator</a>, <a href="#ae23c5bed445884208f7ec2d30c1c5461">isTrap</a>, <a href="#ade5781c13cce7ee39fe5cc54dcebccd8">isVariadic</a>, <a href="#a2eae6ddcf171bdfe8cde452311ff4160">mayLoad</a>, <a href="#a79c717d314d03140128c2b249dc39b31">mayRaiseFPException</a>, <a href="#a1652b3fb1337b788da41bd95a348990c">mayStore</a>, <a href="#a26cbe46f02506e823998e5ae5495cf39">usesCustomInsertionHook</a> and <a href="#a71778bd76509f16d25336d608d1ab61f">variadicOpsAreDefs</a>.</p>

</div>
</div>

### ImplicitOffset {#a2059c24fbfb9da805c6da6073ae60915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::MCInstrDesc::ImplicitOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a> and <a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">implicit_uses</a>.</p>

</div>
</div>

### NumDefs {#af3ad82efc4fd3797a5d9ed70a55354c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::MCInstrDesc::NumDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a3496944fcc473dfe584e6615503a7a76">getNumDefs</a> and <a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a>.</p>

</div>
</div>

### NumImplicitDefs {#a0d45da21f713463669876b3efeaeb95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::MCInstrDesc::NumImplicitDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a9c82d545821ce74a71125df227cde299">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::usePopRet</a>.</p>

</div>
</div>

### NumImplicitUses {#a0213025f97776e13649b1136bae07524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::MCInstrDesc::NumImplicitUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a>, <a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">implicit_uses</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a9c82d545821ce74a71125df227cde299">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::usePopRet</a>.</p>

</div>
</div>

### NumOperands {#a53c07a5f15c9d1ccad93dc1c57f79c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::MCInstrDesc::NumOperands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a0ca904e64ee29c8812ed34e632d3c947">getNumOperands</a>, <a href="#a7695bd2e20788ffc4b645533c018f26e">getOperandConstraint</a>, <a href="#a53879499740e1ed3770a41e9a444ee5b">hasDefOfPhysReg</a> and <a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a>.</p>

</div>
</div>

### Opcode {#adcb5f001406dc2b45024dd582c444e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::MCInstrDesc::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#aee50fcacb786c1fc56168a0c55a4e934">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac18c5827c119a73ea6f07b4ef4649654">llvm::SIInstrInfo::getRegClass</a>, <a href="#a7b41627be5fb4176f9cb16b9ba7f91f7">implicit_defs</a>, <a href="#aeae23d6b812a5aaa9734ebcdeb4f2d26">implicit_uses</a>, <a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>.</p>

</div>
</div>

### OpInfoOffset {#afc35bbedc928d6945522a0b6e3499759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::MCInstrDesc::OpInfoOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a0f4e09a761d45bf0914f26d4c149ddeb">operands</a>.</p>

</div>
</div>

### SchedClass {#abee44339b41568c74881f90122fee878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::MCInstrDesc::SchedClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#a03a564c2840cb8d27314596549fc04b8">getSchedClass</a>.</p>

</div>
</div>

### Size {#a7beb150af9f64d18273d4a98ff37dec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::MCInstrDesc::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="#ad675c21464eb38c355e73c7f72f8160b">getSize</a>.</p>

</div>
</div>

### TSFlags {#a46e0fcca2366f30d5e35b3d7dcb9c65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCInstrDesc::TSFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a60ab44d62adfcff55385762363e231cf">adjustAllocatableRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-mc/#adea9a50e399e313a7a8a5b2007639b49">llvm::ARM_MC::evaluateBranchTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a213afb2c8d115f7e8c72c298e7f54046">llvm::HexagonMCInstrInfo::getAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a692ef5b00648c4f2fc1fc4bf29504a5e">getAddrOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5115f4f0f0213e99431e82c167be0b98">llvm::HexagonMCInstrInfo::getExtendableOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac728d542c58e2a7c3a56cc67b0da9044">llvm::HexagonMCInstrInfo::getExtentAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a38a8fc225b496e9ed8b4856441e08bba">llvm::HexagonMCInstrInfo::getExtentBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armhazardrecognizerfpmlx/#af1064d4637b93e114f1d15631abdc03f">llvm::ARMHazardRecognizerFPMLx::getHazardType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a1161ecb0b43e7af4846b48a4251f2bcd">llvm::HexagonMCInstrInfo::getMemAccessSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a44c5cbb3128220471c20639331ef9356">llvm::HexagonMCInstrInfo::getNewValueOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a395ac8e82757af42f2e2c6c78c7e3cdf">llvm::HexagonMCInstrInfo::getNewValueOp2</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac18c5827c119a73ea6f07b4ef4649654">llvm::SIInstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0d1d1c4a4b150db06882ccf40ce9bc8c">llvm::HexagonMCInstrInfo::hasHvxTmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afa5e44937784daa4bb42a20a52ba5da3">llvm::HexagonMCInstrInfo::hasNewValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa7bc69c19bc9f59a5e5c3161d034a71f">llvm::HexagonMCInstrInfo::hasNewValue2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae08d97008d6d567f2b20287df05d5bd2">llvm::HexagonMCInstrInfo::isAccumulator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a9cfa6311b09fa20140eec60cccbc2e1d">llvm::HexagonMCInstrInfo::isCofMax1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a71c43b3f84faa4daee2b2bc80c515c36">llvm::HexagonMCInstrInfo::isCofRelax1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afd30cb8f783b071d85fc7049b75d157e">llvm::HexagonMCInstrInfo::isCofRelax2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af674c438c3bb3ad548c387a7b03cab15">llvm::HexagonMCInstrInfo::isCVINew</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ada281073abacffc4ccda16549a1a1fe7">llvm::HexagonInstrInfo::isExtendable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a8c525c01df0d371a390190574d22bccc">llvm::HexagonMCInstrInfo::isExtendable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af57335bfd112468cfe89cb1bf7f205be">llvm::HexagonMCInstrInfo::isExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0b58bea5a70bbf57fbd2aaf1a7c6f4bb">llvm::HexagonMCInstrInfo::isExtentSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af9c1fb4944fcf1d6aadc0f51a69b56e9">llvm::HexagonMCInstrInfo::isFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a41c2639831016e233df65de1a6ec6bd3">llvm::HexagonMCInstrInfo::isNewValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5cc023a236173fcdb81a1820c1745eb9">llvm::HexagonMCInstrInfo::isNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a4e4f8751e0c5871b85c84493ba0b2263">llvm::ARCInstrInfo::isPostIncrement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a97d6571ff5232080bec163cd55377545">llvm::HexagonMCInstrInfo::isPredicated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a136b73813b05ae1deee68a06b4c55f5e">llvm::HexagonMCInstrInfo::isPredicatedNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ad81fe27b122fc4b5e48cf9be26d45af8">llvm::HexagonMCInstrInfo::isPredicatedTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a357d567932941548effd2311bdfcc80b">llvm::HexagonMCInstrInfo::isPredicateLate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#ad30c0dba88d2e5f9cc2a9e74fd1e1078">isPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a6fd4bc23e423d06fbc29d17b20a286f4">llvm::ARCInstrInfo::isPreIncrement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ad9ae2e328fd6441af81f22bff80c42b0">llvm::HexagonMCInstrInfo::isRestrictNoSlot1Store</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0d2c795a597e289231bf4d8c1ec7a2ea">llvm::HexagonMCInstrInfo::isRestrictSlot1AOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a11e74a6ead98c7237e37c532e411295d">llvm::HexagonMCInstrInfo::isSolo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a4157ec35dc2d6457245b8772cc3c0602">llvm::HexagonMCInstrInfo::isSoloAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae72685c5f32e967a3708d52677f1226b">llvm::HexagonMCInstrInfo::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a7fb5c7a86107907a7985c93274b02066">llvm::HexagonMCInstrInfo::prefersSlot3</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">MCInstrDesc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstrdesc-cpp">MCInstrDesc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
