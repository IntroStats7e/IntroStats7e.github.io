# Datasets and Resources for Intro Stats 7e

Here is an index of datasets: 

<table>
  {% for row in site.data_index %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>


To download a tab-delimited .txt file suitable for importing into statistical software, click the link to the uploaded .txt file in the dataset's folder, then click the download icon in the upper right corner menu. 


