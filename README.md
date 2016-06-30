
# uri-encodings-fuzzer #

Apply all elements in each proper subset within the power set of LibWhisker's 
encoding subroutines to the URI provided on the command line:

* `encode_uri_hex`
* `encode_uri_randomhex`
* `encode_anti_ids` 
* `encode_unicode`
* `encode_uri_randomcase`

You may need to `cpan install` the following [CPAN](http://search.cpan.org) 
module prerequisites: 

* `List::PowerSet`
* `Math::Combinatorics`

[URI Encodings Fuzzer GitHub repository](http://github.com/decal/uri-encodings-fuzzer)

