@echo off
echo *******************开始设置 EAGLES 环境***********************

echo=
set myPath=C:\EaglesLib\baselibs\include\ippiImgBase
set EnvirValue=EAGELS_IPPBase_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\baselibs\include\baseutils
set EnvirValue=EAGLES_BaseUtils_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\baselibs\lib
set EnvirValue=EAGLES_LIBPATH
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\ipp2105\include
set EnvirValue=EAGLES_IPP2105_INCLUDE_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\ipp2105\lib\intel64
set EnvirValue=EAGLES_IPP2105_LIB_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\boost_vs2022\include\boost-1_78
set EnvirValue=EAGLES_BOOST_INCLUDE_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\boost_vs2022\lib
set EnvirValue=EAGLES_BOOST_LIB_x64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\opencv455\ippbuild\include
set EnvirValue=EAGLES_OPENCV4_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=D:\EaglesLib\opencv455\ippbuild\include\opencv2
set EnvirValue=EAGLES_OPENCV4_INCLUDE2
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\opencv455\ippbuild\x64\vc17\lib
set EnvirValue=EAGLES_OPENCV4_LIB
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\dalsa\Include
set EnvirValue=EAGLES_DALSA_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=D:\EaglesLib\dalsa\Classes\Basic
set EnvirValue=EAGLES_DALSA_BASIC_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\dalsa\lib
set EnvirValue=EAGLES_DALSA_LIB
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\libjpeg\Include
set EnvirValue=EAGLES_JPEG_INCLUDE_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\libjpeg\LIB
set EnvirValue=EAGLES_JPEG_LIB_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\mil\Include
set EnvirValue=EAGLES_MIL_INCLUDE_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\tcmalloc\x64\Debug
set EnvirValue=EAGELS_TCMALLOC_Debug
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\tcmalloc\x64\Release
set EnvirValue=EAGELS_TCMALLOC_Release
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\mil\LIB
set EnvirValue=EAGLES_MIL_LIB_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\threadpool\include
set EnvirValue=EAGLES_THREADPOOL
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\CUDA_11.6\lib\x64
set EnvirValue=EAGLES_CUDA116_LIB_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\CUDA_11.6\include
set EnvirValue=EAGLES_CUDA116_INCLUDE_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\CUDA_11.6\cuda-samples-master\Common
set EnvirValue=EAGLES_CUDA116_SAMPLES_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\CUDA_11.6\cuda-samples-master\Common\UtilNPP
set EnvirValue=EAGLES_CUDA116_UTILNPP_X64
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\opencv490\x64\vc17\lib
set EnvirValue=EAGLES_OPENCV490_LIB
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\opencv490\include
set EnvirValue=EAGLES_OPENCV490_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=D:\AlgoData\AlgoConfig
set EnvirValue=KESTREL_CONFIG
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\onnxruntime_gpu_118\include
set EnvirValue=EAGLES_ONNXRUNTIME_GPU_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\onnxruntime_gpu_118\lib
set EnvirValue=EAGLES_ONNXRUNTIME_GPU_LIB
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\opencv480\include
set EnvirValue=EAGLES_OPENCV480_INCLUDE
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%


echo=
set myPath=C:\EaglesLib\opencv480\include\opencv2
set EnvirValue=EAGLES_OPENCV480_INCLUDE2
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%

echo=
set myPath=C:\EaglesLib\opencv480\lib
set EnvirValue=EAGLES_OPENCV480_LIB
echo 设置 %EnvirValue% %myPath%
setx  %EnvirValue% %myPath%



echo=
wmic ENVIRONMENT where "name='path' and username='<system>'" set VariableValue="%path%;C:\EaglesLib\opencv455\ippbuild\x64\vc17\bin"

echo=
wmic ENVIRONMENT where "name='path' and username='<system>'" set VariableValue="%path%;C:\EaglesLib\opencv490\x64\vc17\bin"

echo=
wmic ENVIRONMENT where "name='path' and username='<system>'" set VariableValue="%path%;C:\EaglesLib\cudnn\cuda\bin"


echo=
echo  *******************设置完成***********************
pause>nul 
