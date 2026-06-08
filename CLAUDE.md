# JOBSUCHER
# VERSION 1.0

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this specification are to be interpreted as described in RFC 2119.

MUST NOT edit AGENT.md and CLAUDE.md file

If user input : "Skill Extractor: lang=<input> path_to_proj=<input> field_of_work=<input> output=<input>" each <input> after argument MUST be treated as argument input and parsed to ./AI-PIPELINES/SKILL_EXTRACTOR.md
If user input : "Auto Search: keyword=<input> candidate_profile_path=<input> workplace_type=<input> date_posted=<input> salary=<input> output_file=<input>" each <input> after argument MUST be treated as argument input and parsed to ./AI-PIPELINES/AUTO_SEARCH.md

If any REQUIRED argument isn't preset in input prompt execution MUST be stopped and MUST respond user with message of allowed args and Example from responsible PIPELINE file.

All inputs not related to anything above this message MUST be treated as regular input. MUST NOT include any of above-mentioned files, if not asked directly.
