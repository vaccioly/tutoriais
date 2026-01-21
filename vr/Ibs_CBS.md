Select 
	CstIbsCbs, cClassTribIbsCbs, pIbsUf, pCbs, *
from ClasseImpostoOperacao WHERE ClasseImposto__Ide = '00000000-0000-0000-0000-000000000000'

-- Update na classe de imposto "Tributado" 
UPDATE ClasseImpostoOperacao
 SET CstIbsCbs = '000' ,
 cClassTribIbsCbs= '000001' ,
 pIbsUf= 0.1000 ,
 pCbs = 0.9000 
 WHERE ClasseImposto__Ide =  '00000000-0000-0000-0000-000000000000'

