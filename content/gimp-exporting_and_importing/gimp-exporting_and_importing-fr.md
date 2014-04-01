## Exporter et importer des images

Vous allez devoir exporter l'image pour pouvoir l'utiliser dans d'autres logiciels ou la transmettre à d'autres personnes pour la publier.

L'enregistrement en JPEG ou en PNG produira des images beaucoup plus légères que le format XCF mais vous allez devoir accepté une perte d'information et -- selon les choix que vous allez faire -- aussi de qualité.

### JPEG

JPEG permet d'obtenir des images très légères. Le poids est défini en fonction d'un critère de compression qui va réinterpréter les détails de l'image en essayant de simplifier le contenu. Le résultat, si on n'y prend pas garde, peut donc produire des pertes d'informations. Lorsque vous enregistrez Gimp va éventuellement afficher des fenêtres pour vous informer des pertes globales occasionnées lors du passage au JPEG (transparence, calques). Ensuite vous obtiendrez la fenêtre permettant de paramétrer la compression : ici, cochez la case permettant d'avoir un aperçu et trouvez le meilleur compromis entre le résultat final sur l'image et le taux de compression.

Le format JPEG est souvent pour exporter les photos.

Pour exporter au format JPEG, assurez vous que l'extension pour le nom du fichier se termine en `.jpg`.

### PNG

Avec le format PNG : quelle que soit la compression appliquée, vous ne subirez aucune perte et il préservera systématiquement tous les détails (sauf en mode couleur indexé). Cela le rend parfait pour des images de qualités d'impression. Cependant, une image au format PNG sera en général plus lourde qu'une image JPEG, elle ne préservera pas les calques, mais conservera transparentes les zones que vous avez définies comme telles. La plupart des options de la fenêtre d'enregistrement en PNG ne modifient pas l'image : passez-les rapidement.

Le format PNG est indispensbale pour exporter des images contenant du texte ou des lignes "claires".

Pour exporter au format PNG, assurez vous que l'extension pour le nom du fichier se termine en `.png`.

## Échange de fichiers

### ORA

Le format de fichier standard Open Raster (ORA) pousse par l'équipe de Gimp, Mypaint et Krita vous permet de travailler avec chacun de ces logiciels sur une même image, avec une perte d'informations minimale (calques, transparences, ...).

## Le PSD de Photoshop

Le formats Photoshop (.psd) reste certainement le plus couramment utilisé après le JPEG.

Il s'agit du format natif de Photoshop et aucun autre logiciel n'est sensé le supporter. L'équipe de Gimp a fait cet effort d'avoir une comprension partielle de ces images. Les calques, les masques, les transparences, les textes seront bien conservés, mais des détails peuvent varier ici ou là dans l'aspect.

Notez que Gimp peut aussi enregistrer au format PSD si vous avez besoin de transmettre votre composition à quelqu'un qui possède Photoshop, qui, lui, ne supporte ni le format XCF, ni le format ORA.

## Les fichiers PDF

Le PDF est un format un peu spécial puisqu'il n'est pas spécifiquement dédié aux images. Pour ouvrir des fichiers PDF dans Gimp, il faudra installer le logiciel libre [Ghostscript](http://www.ghostscript.com/download/gsdnld.html).

Lors de l'ouverture d'un fichier PDF de plusieurs pages, Gimp vous demandera seulement quelle page vous souhaitez ouvrir car Gimp ne peut ouvrir plusieurs pages, il n'a pas été conçu pour ce type de document.
