<?php

use Appwrite\Client;
use Appwrite\Services\Functions;

$client = new Client();

$client
    ->setProject('5df5acd0d48c2') // Your project ID
    ->setKey('919c2d18fb5d4...a2ae413da83346ad2') // Your secret API key
;

$functions = new Functions($client);

$result = $functions->get('[FUNCTION_ID]');