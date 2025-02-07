# Generating bitstreams for KCU
# Led project
.
├── led
│   ├── build.tcl
│   ├── hdl
│   ├── sim
│   └── xdc
│       ├── KCU105_Rev1.0_02292016.xdc
├── led_gui
│   ├── led.cache
│   │   ├── compile_simlib
│   │   │   ├── activehdl
│   │   │   ├── modelsim
│   │   │   ├── questa
│   │   │   ├── riviera
│   │   │   ├── vcs
│   │   │   └── xcelium
│   │   └── wt
│   │       └── project.wpc
│   ├── led.hw
│   │   └── led.lpr
│   ├── led.ip_user_files
│   ├── led.sim
│   └── led.xpr
├── readme.txt
└── xdc
    ├── KCU105_Rev1.0_02292016.xdc
    ├── kcu105-xdc-rdf0349.zip
    └── xdc_notice.txt

led houses the led project in lab-bc format. The build.tcl file in this directory should serve as a basis for future lab-bc (or vivado command line: vivado -mode batch -source build.tcl -log log) bitstream generation.
led-gui is generated using vivado 2024.1.

# xdc
- [kcu 105 xdc file](https://www.xilinx.com/member/forms/download/design-license.html?cid=385293&filename=kcu105-xdc-rdf0349.zip)
# Future plans 
- PCI interface. There is a example project in Future references. Board supports PCI Gen 3, however PCI is forward and backward compatible.

# Future references
- Creating and Using a GTH IBERT Design with the KCU105 board - Oct 09, 2017 ::
  - [ XTP346 - KCU105 GTH IBERT Tutorial (v12.0)](https://www.xilinx.com/member/forms/download/design-license.html?cid=d77a4e72-c593-4d2d-9ff4-93221c7fe0c5&filename=xtp346-kcu105-gth-ibert-c-2017-3.pdf)
  - [See All Versions](https://www.xilinx.com/support/documentation-navigation/see-all-versions.html?xlnxproducttypes=Boards%20and%20Kits&xlnxdocumentid=XTP346)
  - Associated File(s):
    - [ rdf0312-kcu105-gth-ibert-c-2017-3.zip](https://www.xilinx.com/member/forms/download/design-license.html?cid=d1f5f370-e41f-4979-b884-36996f6a0f99&filename=rdf0312-kcu105-gth-ibert-c-2017-3.zip)
  - [https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png](https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png)
- Run, compile, and program the IPI Application for the KCU105 - Oct 09, 2017 ::
  - [ XTP347 - KCU105 IPI Tutorial (v12.0)](https://www.xilinx.com/member/forms/download/design-license.html?cid=e3d4c26b-6437-443e-b55b-0e20991b791e&filename=xtp347-kcu105-ipi-c-2017-3.pdf)
  - [See All Versions](https://www.xilinx.com/support/documentation-navigation/see-all-versions.html?xlnxproducttypes=Boards%20and%20Kits&xlnxdocumentid=XTP347)
  - Associated File(s):
    - [ rdf0313-kcu105-ipi-c-2017-3.zip](https://www.xilinx.com/member/forms/download/design-license.html?cid=8aa2f22d-9cae-475b-ad80-85f553b96d2f&filename=rdf0313-kcu105-ipi-c-2017-3.zip)
  - [https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png](https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png)
- Using MIG to create a DDR4 memory design for the KCU105 - Oct 09, 2017 ::
  - [ XTP348 - KCU105 MIG Tutorial (v12.0)](https://www.xilinx.com/member/forms/download/design-license.html?cid=4d375181-a02c-4fae-93ab-041b6c519c9c&filename=xtp348-kcu105-mig-c-2017-3.pdf)
  - [See All Versions](https://www.xilinx.com/support/documentation-navigation/see-all-versions.html?xlnxproducttypes=Boards%20and%20Kits&xlnxdocumentid=XTP348)
  - Associated File(s):
    - [ rdf0314-kcu105-mig-c-2017-3.zip](https://www.xilinx.com/member/forms/download/design-license.html?cid=dbec6787-94ec-4f0e-ae8a-f0576c91b252&filename=rdf0314-kcu105-mig-c-2017-3.zip)
  - [https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png](https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png)
- Test and Create PCIe x8 Gen3 Design for the KCU105 - Oct 09, 2017 ::
  - [ XTP350 - KCU105 PCIe Tutorial (v12.0)](https://www.xilinx.com/member/forms/download/design-license.html?cid=4ea123e8-6efb-46f0-93b6-27dc40e788a0&filename=xtp350-kcu105-pcie-c-2017-3.pdf)
  - [See All Versions](https://www.xilinx.com/support/documentation-navigation/see-all-versions.html?xlnxproducttypes=Boards%20and%20Kits&xlnxdocumentid=XTP350)
  - Associated File(s):
    - [ rdf0316-kcu105-pcie-c-2017-3.zip](https://www.xilinx.com/member/forms/download/design-license.html?cid=f04e13aa-7b6d-45d6-990b-e62b330a64fd&filename=rdf0316-kcu105-pcie-c-2017-3.zip)
  - [https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png](https://www.xilinx.com/etc.clientlibs/site/clientlibs/xilinx/site-all/resources/imgs/search/pdf.png)
- Restore the Flash Memory of the KCU105 to factory defaults - Oct 09, 2017 ::
  - [ XTP351 - KCU105 Restoring Flash Tutorial (v12.0)](https://www.xilinx.com/member/forms/download/design-license.html?cid=338a04ae-3fe0-4af0-b075-a26d40f89e6b&filename=xtp351-kcu105-restoring-flash-c-2017-3.pdf)
  - [See All Versions](https://www.xilinx.com/support/documentation-navigation/see-all-versions.html?xlnxproducttypes=Boards%20and%20Kits&xlnxdocumentid=XTP351)
