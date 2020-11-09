# **Práctica 1: Web scraping**


## **Descripción**

Esta práctica se ha realizado para la asignatura Tipología y Ciclo de Vida de los Datos de la Universitat Oberta de Catalunya. En ella, se aplican técnicas de web scraping mediante el lenguaje de programación Python para extraer los datos de precios de vivienda la web preciosmundi.com y generar un dataset con ellos.

## **Miembros del equipo**

La actividad ha sido realizada por Juan Alonso Franco Blanco y Juan Prieto Pena.

## **Ficheros del código fuente**

PreciosViviendaPorPais.ipynb

## **Código fuente**

Extrae los precios de la vivienda de la página web del preciosmundi.com 

Para ejecutar el script es necesario instalar la siguientes bibliotecas:

from bs4 import BeautifulSoup

import requests

import pandas as pd

import numpy as np

import time

El script es un notebook que se ejecuta de manera interactiva.

Los registros se almacenan en un archivo de tipo CSV y contienen datos actuales del mes en curso.

El dataset extraido se almacena en PreciosViviendaPorPais.csv

## **DOI del dataset**

https://doi.org/10.5281/zenodo.4256508
