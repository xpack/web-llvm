---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpistream-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TpiStream.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/tpistream-h">llvm/DebugInfo/PDB/Native/TpiStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">llvm/DebugInfo/CodeView/LazyRandomTypeCollection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/recordname-h">llvm/DebugInfo/CodeView/RecordName.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecordhelpers-h">llvm/DebugInfo/CodeView/TypeRecordHelpers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/msf/mappedblockstream-h">llvm/DebugInfo/MSF/MappedBlockStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/hash-h">llvm/DebugInfo/PDB/Native/Hash.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/pdbfile-h">llvm/DebugInfo/PDB/Native/PDBFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawconstants-h">llvm/DebugInfo/PDB/Native/RawConstants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawerror-h">llvm/DebugInfo/PDB/Native/RawError.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">llvm/DebugInfo/PDB/Native/RawTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/tpihashing-h">llvm/DebugInfo/PDB/Native/TpiHashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamreader-h">llvm/Support/BinaryStreamReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include &lt;cstdint&gt;
#include &lt;vector&gt;
</div>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
