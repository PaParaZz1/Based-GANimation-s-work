# README

## java接口形式:

public int ImageTransform(float[] input, float[] output, ImageInfo info, HashMap<ActionUnit, float> au_setting, boolean is_caricature)
(错误码暂用int，也许最后要用对象来封装信息)

## c++ 接口形式
error_code ImageTransform(float* input, float* output, ImageInfo info, unordered_map<ActionUnit, float> au_setting, bool is_caricature)
(ImageInfo 中存储图像基本信息，如宽高等，input和output都是HxWx3的数组)
