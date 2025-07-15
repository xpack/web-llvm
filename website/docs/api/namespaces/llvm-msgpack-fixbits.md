---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/msgpack/fixbits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `FixBits` Namespace Reference

<p>Most significant bits used to identify "Fix" variants in MessagePack. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::msgpack::FixBits { ... }
</div>

## Description {#details}

<p>Most significant bits used to identify "Fix" variants in MessagePack.</p>


<p>For example, FixStr objects encode their size in the five least significant bits of their first byte, which is identified by the bit pattern "101" in the three most significant bits. So FixBits::String contains 0b10100000.</p>


<p>A corresponding mask of the bit pattern is found in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/fixbitsmask">FixBitsMask</a></span>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
