# blockchain_example
Output (mine_block):</br>

{
"index":2,
"message":"A block is MINED",
"previous_hash":"2d83a826f87415edb31b7e12b35949b9dbf702aee7e383cbab119456847b957c",
"proof":533,
"timestamp":"2020-06-01 22:47:59.309000"
}
</br?
Output (get_chain):</br>

{
"chain":[{"index":1,
"previous_hash":"0",
"proof":1,
"timestamp":"2020-06-01 22:47:05.915000"},{"index":2,
"previous_hash":"2d83a826f87415edb31b7e12b35949b9dbf702aee7e383cbab119456847b957c",
"proof":533,
"timestamp":"2020-06-01 22:47:59.309000"}],
"length":2
}
</br>
Output(valid):</br>

{"message":"The Blockchain is valid."}
