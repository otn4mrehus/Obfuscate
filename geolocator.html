<?php
namespace Obfuscator;

/**
 * Class Obfuscator
 * @author Duru Chidozie
 * @copyright 2019
 * @version   1.0.0
 * 
 */

class Obfuscator {

    public static $inputPath;
    public static $outputPath;

    public function __construct($inputPath,$outputPath){
        self::$inputPath=$inputPath;
        self::$outputPath=$outputPath;
    }

    public static function obfuscate(){
        if (!self::$inputPath || !self::$outputPath) {
            die("Error: Not Found - input file or output file\n");
        }

        $data="ob_end_clean();?>";

        $data.=php_strip_whitespace(self::$inputPath);
        
        // compress data
        $data=gzcompress($data,9);
        
        // encode in base64
        $data=base64_encode($data);
        
      
        $out='<?php ob_start();$akugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogoakugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogoakugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogo=\''.$data.'\';eval(gzuncompress(base64_decode($akugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogoakugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogoakugkjugkjgkujfkhdjdutduydihfoufkudysiyikufolufkudikydiufoujfoudkyxujtsyrsrfsytgdihogipigogo)));$v=ob_get_contents();ob_end_clean(); echo $v;?>';
        // write output text
        file_put_contents(self::$outputPath,$out);

    }
}
