# educacao
Teste dos erros de script

<b> Apenas montando um quebra-cabeças <b>

switch($type){
			case 'post':
				if($this->getParam('fetch_type', 'cat_tag') == 'next_prev'){
					$numSlides = 0;
				}else{
					$numSlides = $this->getParam('max_slider_posts', count($this->arrSlides));
					if(intval($numSlides) == 0) $numSlides = 'âˆž';
