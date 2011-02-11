Zeige Sammelbalken, Unterstützungsunterschriften-Formulare und Wahlprogramme als Block

*  Curl für PHP muss installiert sein

Die Seite mit dem JSON-Export muss als Boost-Ausnahme definiert werden

	export/uu/kw2011/json

Folgender PHP-Code ist in einer erstellten Seite notwendig, um einen Block einzublenden

	<?php

	$blockView = module_invoke('pp_kw2011' ,'block', 'view', 0);
	print $blockView['content'];

	?>

