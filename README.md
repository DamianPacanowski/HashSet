# HashSet is a php class for create a hash.

    include('../hash.set.php');
    $hash_set = new hash;
    $hash=str_replace('=','',base64_encode($hash_set->catch('string',1,'key','iv')));

