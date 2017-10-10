# Features of Native Build Systems

<table>
  <tr>
    <th>Tool</th>
    <th>License</th>
    <th>Source</th>
    <th>Community</th>
    <th>Example</th>
    <th>Performance:<br/>Incremental Builds</th>
    <th>Performance:<br/>Task Output Caching</th>
    <th>Performance:<br/>Incremental Subtasks</th>
    <th>Performance:<br/>Compiler Daemon</th>
    <th>Performance:<br/>Parallel Execution</th>
    <th>Performance:<br/>Parallel Download of Dependencies</th>
    <th>Build Scans:<br/>Collaborative Debugging</th>
    <th>Build Scans:<br/>Compare Builds </th>
    <th>Build Scans:<br/>Extend and Customize</th>
    <th>Build Scans:<br/>Track and Export History Across all Builds</th>
    <th>Command-Line Interface:<br/>Task Exclusion</th>
    <th>Command-Line Interface:<br/>Continuous Build</th>
    <th>Command-Line Interface:<br/>Composite Builds</th>
    <th>Command-Line Interface:<br/>Dry Run</th>
    <th>Command-Line Interface:<br/>Continue Execution After Failures</th>
    <th>Command-Line Interface:<br/>Sync Dependency Cache with Repository</th>
  </tr>
  {% for entry in site.data.tools %}
    <tr>
      <td><a href="{{ entry.url }}">{{ entry.title }}</a></td>
      <td><a href="{{ entry.license }}">{{ entry.license | markdownify }}</a></td>
      <td><a href="{{ entry.source }}">{{ entry.source | markdownify }}</a></td>
      <td><a href="{{ entry.community }}">{{ entry.community }}</a></td>
      <td><a href="{{ entry.example }}">{{ entry.example | markdownify }}</a></td>
      <td><a href="{{ entry.performance_incremental_builds }}">{{ entry.performance_incremental_builds }}</a></td>
      <td><a href="{{ entry.performance_task_output_caching }}">{{ entry.performance_task_output_caching }}</a></td>
      <td><a href="{{ entry.performance_incremental_subtasks }}">{{ entry.performance_incremental_subtasks }}</a></td>
      <td><a href="{{ entry.performance_compiler_daemon }}">{{ entry.performance_compiler_daemon }}</a></td>
      <td><a href="{{ entry.performance_parallel_execution }}">{{ entry.performance_parallel_execution }}</a></td>
      <td><a href="{{ entry.performance_parallel_download_of_dependencies }}">{{ entry.performance_parallel_download_of_dependencies }}</a></td>
      <td><a href="{{ entry.build_scans_collaborative_debugging }}">{{ entry.build_scans_collaborative_debugging }}</a></td>
      <td><a href="{{ entry.build_scans_compare_builds }}">{{ entry.build_scans_compare_builds }}</a></td>
      <td><a href="{{ entry.build_scans_extend_and_customize }}">{{ entry.build_scans_extend_and_customize }}</a></td>
      <td><a href="{{ entry.build_scans_track_and_export_history_across_all_builds }}">{{ entry.build_scans_track_and_export_history_across_all_builds }}</a></td>
      <td><a href="{{ entry.command_line_interface_task_exclusion }}">{{ entry.command_line_interface_task_exclusion }}</a></td>
      <td><a href="{{ entry.command_line_interface_continuous_build }}">{{ entry.command_line_interface_continuous_build }}</a></td>
      <td><a href="{{ entry.command_line_interface_composite_builds }}">{{ entry.command_line_interface_composite_builds }}</a></td>
      <td><a href="{{ entry.command_line_interface_dry_run }}">{{ entry.command_line_interface_dry_run }}</a></td>
      <td><a href="{{ entry.command_line_interface_continue_execution_after_failures }}">{{ entry.command_line_interface_continue_execution_after_failures }}</a></td>
      <td><a href="{{ entry.command_line_interface_sync_dependency_cache_with_repository }}">{{ entry.command_line_interface_sync_dependency_cache_with_repository }}</a></td>
    </tr>
  {% endfor %}
</table>
