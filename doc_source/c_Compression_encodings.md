# Compression Encodings<a name="c_Compression_encodings"></a>

**Topics**
+ [Raw Encoding](c_Raw_encoding.md)
+ [AZ64](az64-encoding.md)
+ [Byte\-Dictionary Encoding](c_Byte_dictionary_encoding.md)
+ [Delta Encoding](c_Delta_encoding.md)
+ [LZO](lzo-encoding.md)
+ [Mostly Encoding](c_MostlyN_encoding.md)
+ [Runlength Encoding](c_Runlength_encoding.md)
+ [Text255 and Text32k Encodings](c_Text255_encoding.md)
+ [ZSTD](zstd-encoding.md)

<a name="compression-encoding-list"></a>A compression encoding specifies the type of compression that is applied to a column of data values as rows are added to a table\.

If no compression is specified in a CREATE TABLE or ALTER TABLE statement, Amazon Redshift automatically assigns compression encoding as follows:
+ Columns that are defined as sort keys are assigned RAW compression\.
+ Columns that are defined as BOOLEAN, REAL, or DOUBLE PRECISION data types are assigned RAW compression\.
+ All other columns are assigned LZO compression\.

The following table identifies the supported compression encodings and the data types that support the encoding\.

[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/redshift/latest/dg/c_Compression_encodings.html)