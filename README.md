4 Week internship of VLSI using VSDSquadron Mini RISC-V Development kit 
In this mini research project, I'm exploring Very Large Scale Integration (VLSI) using the VSDSquadron Mini RISC-V Development kit. It's a small but powerful tool that helps understand how to design digital circuits. I'm diving into how it works, how to make it better, and how to use it effectively. By looking at different designs, trying new things, and measuring how well they work, I hope to learn more about VLSI design. This research is about exploring and learning, and it's all about the fascinating world of VLSI engineering.This repositiry is intended to document the learning outcomes and experience of a 4-week workshop on VLSI and RISC-V using VSDSquadron Mini RISC-V Development kit.

<details>
<summary>Introduction</summary>
<br>
Software required for the program has been installed, with 100 GB allocated for storage and 8 TB for the virtual machine
</details>

<details>
<summary> OS AND SOFTWARE needed</summary>
<br>
Ubuntu, Oracle Virtual Machine and packages needed are Yosys,gtkwave,iverilog,OpenSTA,Magic
</details>

<details>
  <summary> TASK 1 </summary>
  
  Installed all required Softwares for the project.
  <br>
  ![yosys](https://github.com/akhilgwoda2003/README/assets/146440570/99e80222-e1d9-4429-b51e-aaa3c5851363)
  DKMS( Install completion).
  <br>
 ![DKMS( Install completion)](https://github.com/akhilbhandary21/vsd/assets/160320450/993c244f-944b-4937-a0db-925d97ad06ff)

 ![SUDO](https://github.com/akhilbhandary21/vsd/assets/160320450/201e277d-eb07-48a9-945d-b626014e9870)

SUDO APT-GET INSTALL GIT
  <br>

![SUDO APT-GET INSTALL GIT](https://github.com/akhilbhandary21/vsd/assets/160320450/2ee521ea-f413-4239-82fd-8e83e213a01f)

![SUDO APT INSTALL VM](https://github.com/akhilbhandary21/vsd/assets/160320450/6b4ff3fa-1501-4f00-a1c3-993b4561b16b)

![SUDO APT INSTALL VIM](https://github.com/akhilbhandary21/vsd/assets/160320450/74b7770c-1415-491a-a7af-952b2ff014fb)

![SUDO APT INSTALL IVIM](https://github.com/akhilbhandary21/vsd/assets/160320450/69eaa4f4-d6a0-4cc8-a699-936452fa3f75)

![SUDO APT GET INSTALL IVERILOG](https://github.com/akhilbhandary21/vsd/assets/160320450/d4f129af-f313-426b-bb64-749fb161cff3)

![SUDO APT GET INSTALL GIT](https://github.com/akhilbhandary21/vsd/assets/160320450/dae053ff-3a96-4f39-8423-a618a8fb2381)

![SUDO APK INSTALL GTKWARE](https://github.com/akhilbhandary21/vsd/assets/160320450/7ce0607e-8725-407b-ad56-c27632889419)

</details>

<details>
  <summary> TASK 2 </summary>

 BLOCK DIAGRAM,WAVEWFORM OF CARPARKING SYSTEM
  <br>
 ![BLOCK DIAGRAM](https://github.com/akhilbhandary21/vsd/assets/160320450/b4036fff-b3cc-4384-93da-15e34d3b4560)

![WAVEFORM](https://github.com/akhilbhandary21/vsd/assets/160320450/c5933053-65d4-47ce-9d15-5cb4c2d48dce)

![MAPPING](https://github.com/akhilbhandary21/vsd/assets/160320450/f5e10ae2-1f09-4f5e-9ebd-a5f3a7c64a25)


</details>

<details>
<summary>LED BLINK </summary>
<br>
LED BLINK USING VLSI using VSDSquadron Mini RISC-V Development kit .
![LED BLINK(test)](https://github.com/akhilbhandary21/vsd/assets/160320450/8c0eb2d4-3ea7-47a9-94ab-4df713aa21d4)

![YOSIS OPEN SYNTHESIS](https://github.com/akhilbhandary21/vsd/assets/160320450/1a361544-82dd-4f26-a62f-d030dbbee2eb)
  
</details>


<details>
  <summary> TASK 3: Installion of RTL and Test bench files and chexk the basic functional simulation. </summary>

  RTL and TB files
  <br>
![WhatsApp Image 2024-04-18 at 9 20 16 PM](https://github.com/akhilgwoda2003/README/assets/146440570/a19e9cbd-42fb-44b0-ad0d-51a9e1297a69)

  Basis of functional simulation
  <br>
  ![Screenshot from 2024-02-25 13-36-48](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/7d5ead33-1c86-4262-b9d3-6f503af320e0)     



  
  REQUIRED PICTURES.
  ![task3out](https://github.com/akhilbhandary21/vsd/assets/160320450/91814ec3-ad1e-448c-ae8d-72025818c3df)
  

</details>

<details>
  <summary> TASK 4:Read the example verilog file,synthesis and write the netlist.  </summary>

  Invoking yosys inside verilog_code file:
  
  <code>yosys</code>
  <br>
  ![WhatsApp Image 2024-04-11 at 12 43 15 PM (2)](https://github.com/akhilgwoda2003/README/assets/146440570/e6d1eb2e-ec60-434f-8775-82bbaef7ea4e)


  Reading the Library:

  <code>read_liberty -lib /home/kumar123/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib</code>
  <br>
  ![read lib](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/06e8f261-67e4-4b90-a452-2cb12e2f8b44)

  Reading the Design:

  <code>read_verilog good_mux.v</code>
  <br>
  ![read verilog](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/30c76fdf-fdf5-4096-a4bd-e119ddaf82bd)

  Specifying the module that we are synthesizing:

  <code>synth -top good_mux</code>
  <br>
  ![synth](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/401752ce-8d5b-451f-b50b-346be328f5b4)

  To generate the netlist use abc liberty:

  <code>abc -liberty /home/kumar123/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib</code>
  <br>
  ![abc liberty](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/fc9fc79c-ac05-445e-ab89-547127a90ca5)

  To see the graphical version of the logic:

  <code>show</code>
  <br>
  ![show](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/17c7dc2d-cbc5-4b25-9182-7087d1d2f0f4)

  To write the netlist:

  <code>write_verilog good_mux_netlist.v</code>
  <br>
  ![write verilog](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/e2818095-8900-40ce-9e8c-758b6823e665)

  Using the switch '-noattr' to get the simplified version of netlist file:

  <code>write_verilog -noattr good_mux_netlist.v</code>
  <br>
  ![write verilog noattr](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/98236726-aeff-4243-a6bb-52a899ffdf0b)

  To open the netlist:

  <code>!gvim good_mux_netlist.v</code>
  <br>
  ![gvim](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/99c3eafe-2147-4070-8959-147d75b22bf4)

  ![gvim code](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/36b34545-5ce3-4788-831a-f8450153fd68)


  TASK 4 REQUIRED DETAILED PICTURE
  ![c2](https://github.com/akhilbhandary21/vsd/assets/160320450/01c5f3ca-242b-4d81-9d8a-6f3049c6a96a)
  ![c1](https://github.com/akhilbhandary21/vsd/assets/160320450/c15e113f-f60d-40dc-8fb2-a23a731487d1)
  ![c5](https://github.com/akhilbhandary21/vsd/assets/160320450/d6d23587-8c2b-4ebd-8386-89af26d0457b)
  ![c4](https://github.com/akhilbhandary21/vsd/assets/160320450/559af1a0-0a43-4bc5-a124-ef92be8b9246)
  ![c3](https://github.com/akhilbhandary21/vsd/assets/160320450/30a5226d-5459-4cae-8d53-14fe5e2548c2)


 OUTPUTS:


  ![1output good mux](https://github.com/akhilbhandary21/vsd/assets/160320450/ced42b8a-f395-4401-8a61-2b8f63f6e3a5)
  ![output ](https://github.com/akhilbhandary21/vsd/assets/160320450/31c6a7b7-c9a6-412c-9c5f-773c6c094891)
  


</details>

<details>
  <summary> TASK 5: Read the project files and write the netlist and verify the wave forms. </summary>
Check the Gtkwave for the design

<code> iverilog iiitb_cps.v</code>
<code>./a.out</code>
<code>gtkwave iiitb_cps.vcd</code>
<br>
![gtkwave](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/91c7e561-947e-48f9-9c77-6e9d60f8e50a)

   To Generate the netlist extract the git code file of car parking system project


  Invoking yosys inside iiitb_cps file
  
<code>yosys</code>
<br>
  ![WhatsApp Image 2024-04-11 at 12 43 15 PM (2)](https://github.com/akhilgwoda2003/README/assets/146440570/e6d1eb2e-ec60-434f-8775-82bbaef7ea4e)

Reading the Library:

<code>read_liberty -lib /home/kumar123/iiitb_cps/lib/sky130_fd_sc_hd_tt_025C_ 1v80.lib</code>
<br>
![read lib real](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/40674605-992c-4594-b2be-9dd34df64d05)

Read verilog file:

<code>read_verilog iiitb_cps.v</code>
<br>
![read verilog real](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/7e51a141-cdd4-416f-812a-be4e05654e6c)

Synthesizing the project module:

<code>synth -top iiitb_cps</code>
<br>
![synth real](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/e3309e3a-f420-4b71-b0a3-507c51eaa55b)

Generate the netlist:

<code>abc -liberty /home/kumar123/iiitb_cps/lib/sky130_fd_sc_hd_tt_025C_1v80.lib</code>
<br>
![abc lib real](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/928219a8-95e1-4902-a113-99d4f422f6ad)

To write the netlist:

<code>write_verilog netlist.v</code>

Using the switch '-noattr' to get the simplified version of netlist file:

<code>write_verilog -noattr netlist.v</code>

To see graphical representation of the logic:
<code>show</code>
![show dot](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/ff7e6747-76f4-4ba3-8e59-d6a60df887c0)

To open the netlist:
<code>!gvim netlist.v</code>

Here is the clear view of circuit:

[output.pdf](https://github.com/KumarKarthikeya/VLSI-VSD/files/14545854/output.pdf)

Check the whether the netlist will match the design:
<code>iverilog ../iiitb_cps/verilog_model/primitives.v ../iiitb_cps/verilog_model/sky130_fd_sc_hd.v netlist.v iiitb_cps.v</code>

<code> ./a.out</code>

<code> gtkwave iiitb_cps.vcd</code>

Gtkwave of the netlist:
![gtk2](https://github.com/KumarKarthikeya/VLSI-VSD/assets/72381320/e3e5a93c-c1d4-4b1f-847e-4a6a68a79baa)

TASK 5 REQUIRED PICTURE IN DETAIL.
![DESIGN AND SYNTHESIS](https://github.com/akhilbhandary21/vsd/assets/160320450/4525cfbd-0e22-4785-853c-e110842e7fd8)
![CPS NETLIST](https://github.com/akhilbhandary21/vsd/assets/160320450/5b6ade9e-da82-4bef-a4f3-f8901bfa5641)
![XDOT](https://github.com/akhilbhandary21/vsd/assets/160320450/d28be2b0-200c-4830-b104-007d104fcaf8)
![VERILOG FILES](https://github.com/akhilbhandary21/vsd/assets/160320450/8c86f6b5-1b42-4e2c-b7c9-1bff1e558649)
![IIITB CPS](https://github.com/akhilbhandary21/vsd/assets/160320450/d25d0fec-0c47-4453-ac60-fe5e704c133d)
![IIITB CPS GVIM](https://github.com/akhilbhandary21/vsd/assets/160320450/032d7495-c2b4-4454-8378-49345012b3f7)
![GTK WAVE WAVEFORM](https://github.com/akhilbhandary21/vsd/assets/160320450/ac8d04df-3484-46ed-a1b3-bcb786b51550)
![DOT VIEWER](https://github.com/akhilbhandary21/vsd/assets/160320450/fab63e9c-36c2-4ed4-b1ae-bf671a1adf55)
![DOT VIEWER (2)](https://github.com/akhilbhandary21/vsd/assets/160320450/56e9e804-98b3-4b7b-9ce1-ed46695554bd)
![DOT POINT](https://github.com/akhilbhandary21/vsd/assets/160320450/270f24bd-2a5d-48b1-92bb-94b19855045e)


</details>

