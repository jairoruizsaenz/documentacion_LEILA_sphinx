Ejemplos - Reporte
========================

reporte.generar_reporte
-----------------------

Crea un reporte de calidad de datos en formato HTML.

    .. code-block:: python

        >>> # Se importan las funciones de la librería
        >>> from leila.reporte import generar_reporte

        >>> # Se invoca la función para generar el reporte de calidad de datos
        >>> generar_reporte(df=df_datos, 
        >>>                 titulo='Perfilamiento datos COVID-19 - Colombia', 
        >>>                 archivo='perfilamiento.html')

        --------------------------------------------------------------
        Se ha generado el reporte "perfilamiento.html"
        11:52:29 AM (01 min 4 seg)
        --------------------------------------------------------------

.. figure:: https://github.com/ucd-dnp/leila/blob/gh-pages/sphinx/source/_static/image/vista_reporte.gif?raw=true
    :align: center
    :alt: Ejemplo de reporte
    :figclass: align-center

    Ejemplo de reporte