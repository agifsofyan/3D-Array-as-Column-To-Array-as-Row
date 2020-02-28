public static function 3D_flip_array($array){
  $out = array();
  
  foreach ($array as $key => $subarr)
  {
    foreach ($subarr as $subkey => $subvalue)
    {
      foreach($subvalue as $childkey => $childvalue)
      {
        $out[$key][$childkey][$subkey] = ($childvalue);
      }
    }
  }
  
  return $out;
 }
