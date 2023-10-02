github.dismiss_out_of_range_messages

warn("PR is classed as Work in Progress") if github.pr_title.include? "[WIP]"

# ktlint
checkstyle_format.base_path = Dir.pwd
Dir["*/build/reports/ktlint-results.xml"].each do |file|
  checkstyle_format.report file
end
