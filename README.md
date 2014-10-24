HID device database
===================

This repository contains a bunch of hid-recorder traces of
HID devices we have already encountered.

The tree is organised as such:
- events/: root of the database
- events/DEVICE_TYPE: the HID recordings, classed by the
  DEVICE_TYPE they belong to.
- events/expected_evemu/3.YY.x/: some evemu recordings of what to
  expect from the HID device when connected to the host using
  a kernel v3.YY.

Note that the evemu traces only contain the longterm and stable
versions of the kernel. Maintaining each and every intermediate
version was too painful to be useful.
