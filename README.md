# Unet_from_scratch

Dans le cadre de ce projet, nous aimerions utiliser un algorithme de deep learning adapté au traitement des images pour faire de la segmentation binaire sur des images RGB. Ici nous allons étudier des images satellites, notre objectif est de pouvoir détecter les glissements de terrain sur un territoire montagneux. Nous avons à notre disposition un dataset extrait de Kaggel initié par l'IARAI (Institute of Advanced Research in Artificial Intelligence) dans le projet landslide4sense 2022. Vous pouvez lire l'article de recherche en lien avec ce sujet au lien suivant : https://arxiv.org/abs/2206.00515

lien du dataset : https://www.kaggle.com/code/niyarrbarman/binary-image-segmentation-using-segformer/input

Dans ce notebook nous allons recoder l'algorithme Unet pour effectuer la classification sémantique de nos images, nous procèderons par la suite à de la data augmentation si besoin.
