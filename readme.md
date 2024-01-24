#### Token Streaming Application in Aztec

Written in Noir, this app extends the Token standard and able to stream the token to any Aztec address. User can
start the stream by calling the `create_stream` function by passing required params like receiver address, amount and flow rate. Users can similarly call `withdraw_from_stream` and `cancel_stream` as well. Since its the extension of Token standard it can support the Private Streaming as well, provided user must have the respective token.
