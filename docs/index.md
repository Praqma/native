# Features of Native Build Systems

<table>
  <tr>
    <th></th>
    <th>Bazel</th>
    <th>Buck</th>
    <th>Conan</th>
    <th>Gradle</th>
    <th>Make</th>
    <th>SCons</th>
  </tr>
  {% for entry in site.data.features %}
    <tr>
      <td>{{ entry.title }}</td>
      <td><a href="{{ entry.bazel }}">{{ entry.bazel | markdownify }}</a></td>
      <td><a href="{{ entry.buck }}">{{ entry.buck | markdownify }}</a></td>
      <td><a href="{{ entry.conan }}">{{ entry.conan | markdownify }}</a></td>
      <td><a href="{{ entry.gradle }}">{{ entry.gradle | markdownify }}</a></td>
      <td><a href="{{ entry.make }}">{{ entry.make | markdownify }}</a></td>
      <td><a href="{{ entry.scons }}">{{ entry.scons | markdownify }}</a></td>
    </tr>
  {% endfor %}
</table>

## Interest over Time on Google Trends

<div markdown="0">
  <script type="text/javascript" src="https://ssl.gstatic.com/trends_nrtr/1154_RC03/embed_loader.js"></script>
  <script type="text/javascript">
    trends.embed.renderExploreWidget("TIMESERIES", {"comparisonItem":[{"keyword":"bazel build","geo":"","time":"today 12-m"},{"keyword":"buck build","geo":"","time":"today 12-m"},{"keyword":"conan build","geo":"","time":"today 12-m"},{"keyword":"gradle build","geo":"","time":"today 12-m"},{"keyword":"scons build","geo":"","time":"today 12-m"}],"category":0,"property":""}, {"exploreQuery":"q=bazel%20build,buck%20build,conan%20build,gradle%20build,scons%20build&date=today 12-m,today 12-m,today 12-m,today 12-m,today 12-m","guestPath":"https://trends.google.com:443/trends/embed/"});
  </script>
</div>
