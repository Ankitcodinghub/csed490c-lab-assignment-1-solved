# csed490c-lab-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSED490C Lab Assignment 1 Solved](https://www.ankitcodinghub.com/product/csed490c-solved-6/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115857&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED490C Lab Assignment 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1 Objective

The purpose of this lab is to introduce the students to the CUDA API by implementing vector addition. The students will implement vector addition by writing the GPU kernel code as well as the associated host code.

2 Instructions

The code template in template.cu provides a starting point and handles the import and export as well as the checking of the solution. Students are expected to insert their code in the sections demarcated with //@@. Students are expected to leave the other code unchanged. Edit the skeleton code to perform the following:

• Allocate device memory

• Copy host memory to device

• Initialize thread block and grid dimensions

• Invoke CUDA kernel

• Copy results from device to host

• Free device memory

• Write the CUDA kernel

Compile the template with the provided Makefile. The executable generated as a result of compilation can be run using the following code:

./VectorAdd template -e &lt;expected.raw&gt; -i &lt;input1.raw&gt;,&lt;input2.raw&gt; -o &lt;output.raw&gt; -t vector

, where &lt;expected.raw&gt; is the expected output, &lt;input0.raw&gt;,&lt;input1.raw&gt; is the input dataset, and &lt;output.raw&gt; is an optional path to store the results. README.md has details on how to build libgputk, template.cu and the dataset generator.

When you work on the department’s computing cluster, you need to request a computing node with NVIDIA GPUs using the following command:

srun -p titanxp -N 1 -n 6 –mem=32G –gres=gpu:2 –pty /bin/bash -l

Note that you need to run ccmake and compile your kernel on the master node because the required utilities are not installed on GPU computing nodes (We are working on getting them installed on GPU computing nodes). Then, you can execute your compiled program on a GPU computing node.

3 What to Turn in

Submit a report that includes the following:

1. Answers to the following questions.

(a) How many floating point operations are being performed in your vector add kernel? Explain.

(b) How many global memory reads are being performed by your kernel? Explain.

(c) How many global memory writes are being performed by your kernel? Explain.

2. Your version of template.cu.

3. Execution times of the kernel with the input data generated by the dataset generator (in a tableor graph). Please include the system information where you performed your evaluation. For time measurement, use gpuTKTime start and gpuTKTime stop functions (You can find details in libgputk/README.md).
