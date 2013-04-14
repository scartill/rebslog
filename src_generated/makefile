
*.erl *.hrl *.asn1db: ../src/*.asn
	erlc -bper_bin +optimize +undec_rest +compact_bit_string +noobj ../src/*.asn

clean:
	rm -f *.erl *.hrl *.asn1db

.PHONY: clean
	
