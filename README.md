##Snappy D Deimos Bindings

From [code.google.com/p/snappy](https://code.google.com/p/snappy/):
"Snappy is a compression/decompression library. It does not aim for maximum compression, or compatibility with any other compression library; instead, it aims for very high speeds and reasonable compression. For instance, compared to the fastest mode of zlib, Snappy is an order of magnitude faster for most inputs, but the resulting compressed files are anywhere from 20% to 100% bigger. On a single core of a Core i7 processor in 64-bit mode, Snappy compresses at about 250 MB/sec or more and decompresses at about 500 MB/sec or more.

Snappy is widely used inside Google, in everything from BigTable and MapReduce to our internal RPC systems. (Snappy has previously been referred to as “Zippy” in some presentations and the likes.)

For more information, please see the README. Benchmarks against a few other compression libraries (zlib, LZO, LZF, FastLZ, and QuickLZ) are included in the source code distribution. The source code also contains a formal format specification, as well as a specification for a framing format useful for higher-level framing and encapsulation of Snappy data, e.g. for transporting Snappy-compressed data across HTTP in a streaming fashion."

###Version: 1.1.0

Status: All of the standard api is ported.