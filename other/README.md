- `sonar-log-api-testdata.sl3` is format 3 version 1 with channels 0, 2, 5 and 9.
  In each case of channel 9, flag 0x0008 is also set and required extra steps
  when parsed.

- `format3_version2.sl3` if format 3 version 2 with channels 0, 1, 2, 5, 7 and 8.

- `corrupt_partly.sl2` is a manually modified (corrupt) version of small.sl2.
  where the first frame header have some bytes deleted.