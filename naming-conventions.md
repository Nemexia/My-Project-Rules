Category	Convention	Examples

Classes, Structs, Enums, Type aliases, Concepts	PascalCase	User, UserConfig, ConnectionState, UserId, Serializable
Namespaces, Functions, Member functions, Local variables, Parameters, Constants	snake_case	networking, calculate_score, user_name, max_connections
Data members, Static data members	snake_case_	user_name_, instance_count_
Enum values	PascalCase	Connected, Disconnected
Generic template parameters	Short names	T, U, V
Semantic template parameters	PascalCase	Element, Allocator
Macros, Header guards	UPPER_SNAKE_CASE	PROJECT_VERSION, PROJECT_CONFIG_HPP
Files	snake_case	connection_manager.hpp
Boolean functions	is_*, has_*, can_*, should_*, needs_*	is_valid, has_value
Boolean variables	snake_case	connected, enabled, valid
Simple getters	Noun	name()
Semantic retrieval	get_*	get_remote_profile()
Mutating operations	Semantic verb	rename(), activate()
Setters	set_* when appropriate	set_timeout()
Factories	make_* / create_*	make_connection(), create_account()
Search, loading, saving, parsing, calculation, validation	find_*, load_*, save_*, parse_*, calculate_*, validate_*	find_user(), load_config()
Conversion	to_* / from_*	to_string(), from_json()
IDs, Counts, Indices, Sizes	*_id, *_count, *_index, *_size	user_id, user_count
Pointers, References, Smart pointers, Views, Spans	No type-based suffix	user, users
Acronyms	Treat as words	HttpServer, JsonParser, TcpConnection
Lambdas	Normal variable naming	is_valid
Operators	Standard C++ syntax	operator==