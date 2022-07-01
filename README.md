### IMX258 sensor test patterns

#### GOAL: Provide a raw stream file with frames contents differing from one frame to next

`stream_packed.bin`   - Raw image stream in IPU3 specific packed format `(ip3G)`

`stream_unpacked.raw` - Raw image stream in 16-bit bayer format derived from stream_packed.bin `(2150x1560)`

ppm/ - Files representing consective frames from stream_unpacked.raw
       (processed using raw2pnm tool)


v4l2-ctl stream hack `0001-v4l2-ctl-update-test-pattern-on-buffer-write.patch`
