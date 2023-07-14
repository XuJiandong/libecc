
EC_UTILS := ../build/ec_utils


generate:
	$(EC_UTILS) gen_keys SECP256R1 ECDSA secp256r1_keypair1

sign:
	$(EC_UTILS) sign SECP256R1 ECDSA SHA256 myfile secp256r1_keypair1_private_key.bin myfile_sig.bin

verify:
	$(EC_UTILS) verify SECP256R1 ECDSA SHA256 myfile secp256r1_keypair1_public_key.bin myfile_sig.bin
